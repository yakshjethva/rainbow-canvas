# Rainbow Canvas

The Rainbow Canvas is a fun and interactive project that allows users to draw colorful lines on a canvas, creating a beautiful rainbow effect as they draw. Users can adjust the brush size and clear the canvas to start drawing again.

![Rainbow Canvas Preview](./preview.png)

## Features

- Draw colorful lines on the canvas with a continuously changing rainbow effect.
- Adjust the brush size to create thicker or thinner lines.
- Clear the canvas with the "Clear" button to start drawing again.

## Usage

1. Open the `index.html` file in your web browser.
2. Move your mouse cursor over the canvas to draw with the rainbow effect.
3. Use the "Clear" button to clear the canvas and start drawing again.
4. Adjust the brush size using the input range slider for different line thickness.

## Implementation Details

- The project is built using HTML, CSS, and vanilla JavaScript.
- The drawing logic utilizes the `canvas` element and its 2D context.
- The color of the drawing line is changed using the HSL (Hue, Saturation, Lightness) color model to create the rainbow effect.
- Mouse events (`mousedown`, `mouseup`, `mousemove`) are used to track the drawing action.
- The "Clear" button triggers the `clearCanvas` function to clear the canvas.

## Try It Out

You can try out the Rainbow Canvas by cloning this repository and opening the `index.html` file in your web browser.

```bash
git clone https://github.com/yakshjethva/rainbow-canvas.git
cd rainbow-canvas
```

## Contributing

Contributions to this project are welcome! If you find any bugs or want to suggest improvements, please feel free to open an issue or submit a pull request.

    Fork the repository.
    Create your branch: git checkout -b feature/YourFeatureName
    Commit your changes: git commit -m 'Add some feature'
    Push to the branch: git push origin feature/YourFeatureName
    Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
