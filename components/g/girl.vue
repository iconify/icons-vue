<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oaatlebms"/><radialGradient id="SVGuhHhBeRX" cx="22.726" cy="18.492" r="23.02" gradientTransform="matrix(.8903 -.4554 -.2657 -.5195 7.402 129.46)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGuhHhBeRX)" class="gah49lbmh"/><radialGradient id="SVGNK3TfegD" cx="13.53" cy="8.481" r="15.43" gradientTransform="matrix(.8381 -.5456 -.2765 -.4247 4.54 130.507)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".699" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGNK3TfegD)" class="i5u887duc"/><radialGradient id="SVG9lGr2n9Q" cx="37.584" cy="18.492" r="23.02" gradientTransform="matrix(-.8903 -.4554 .2657 -.5195 133.827 136.225)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG9lGr2n9Q)" class="u-2_5vb1m"/><radialGradient id="SVGP2xjqbwY" cx="28.388" cy="8.481" r="15.43" gradientTransform="matrix(-.8381 -.5456 .2765 -.4247 135.912 138.613)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".699" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGP2xjqbwY)" class="d9aio9puv"/><path class="b1mggr2wy"/><path class="hv76tibji"/><path class="fb93hlbxq"/><path class="ipbc-abbm"/><g class="y73_33btq"><ellipse class="j9rau6c1y"/><ellipse class="or_iiybfl"/></g><path class="wf7_n7cap"/><path class="levc5acic"/><radialGradient id="SVGawcXFbYJ" cx="64.019" cy="74.01" r="51.664" gradientTransform="rotate(181.118 -.087 62.4)scale(-1 .9737)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGawcXFbYJ)" class="n-nvbnzht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:girl" /></template>
<style>
.b1mggr2wy {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M26.79 94.84c-7.33 0-13.29-5.71-13.29-12.73s5.96-12.73 13.29-12.73h75.43c7 0 12.29 5.47 12.29 12.73s-5.28 12.73-12.29 12.73z");
}

.d9aio9puv {
  d: path("m111.47 123.82l-1.58-7.48l13.79 3.44s.97-13.3-10.9-20.98c-13.01-8.42-26.52 10.59-17.61 19.24c6 5.81 16.3 5.78 16.3 5.78");
}

.fb93hlbxq {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M69.07 87.09a1.6 1.6 0 0 0-.42-.11h-9.3c-.14.02-.28.05-.42.11c-.84.34-1.31 1.22-.91 2.14c.4.93 2.25 3.54 5.98 3.54s5.58-2.61 5.98-3.54c.4-.92-.06-1.8-.91-2.14");
}

.gah49lbmh {
  d: path("m16.53 123.82l1.58-7.48l-13.79 3.44s-.97-13.3 10.9-20.98c13.01-8.42 27.99.55 27.99.55s-1.47 10.04-10.38 18.69c-6 5.81-16.3 5.78-16.3 5.78");
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.hv76tibji {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M64 122.43c-18.05 0-43.46-16.17-43.46-52.12c0-33.44 19.09-59.64 43.46-59.64s43.46 26.2 43.46 59.64c0 35.95-25.41 52.12-43.46 52.12");
}

.i5u887duc {
  d: path("m16.53 123.82l1.58-7.48l-13.79 3.44s-.97-13.3 10.9-20.98c13.01-8.42 26.52 10.59 17.61 19.24c-6 5.81-16.3 5.78-16.3 5.78");
}

.ipbc-abbm {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M32.45 68.38c4.07-5.82 13.42-6.04 18.48-1.5c.98.88 2.25 2.17 1.61 3.61c-.58 1.31-1.96 1.37-3.12.92c-3.24-1.25-6.42-1.97-9.9-1.34c-.9.16-1.77.42-2.63.7c-.69.22-1.31.62-2 .83c-1.89.59-3.57-1.52-2.44-3.22m60.56 3.16c-2.87-1.27-5.86-2.01-9.02-1.65c-1.7.19-3.34.66-4.92 1.31c-1.08.45-2.3.86-3.22-.17c-2.41-2.68 3.32-5.81 5.2-6.52c3.55-1.34 7.66-1.01 10.98.79c1.39.75 2.96 1.85 3.68 3.3c.86 1.72-.9 3.67-2.7 2.94");
}

.j9rau6c1y {
  cx: 42.4px;
  cy: 80.3px;
  rx: 6.48px;
  ry: 6.71px;
}

.levc5acic {
  fill: var(--svg-color--543930, #543930);
  d: path("M103.86 18.49c-5.97-6.22-11.63-8.85-12.18-8.92c-6.93-3.17-15.85-5.58-27.42-5.58c-50.85 0-54.38 41.63-52.33 59.88c1.8 16.09 11.49 20.12 11.49 20.12l-1.38-15.82s18.2-4.79 27.8-12.22s14.03-13.79 14.03-13.79s3.24 4.8 13.91 13.67s28.26 12.59 28.26 12.59l.07 15.53s8.46-3.94 9.88-20.07c1.76-20.21-.66-32.3-12.13-45.39");
}

.n-nvbnzht {
  d: path("M103.86 18.49c-5.97-6.22-11.63-8.85-12.18-8.92c-6.93-3.17-15.85-5.58-27.42-5.58c-50.85 0-54.38 41.63-52.33 59.88c1.8 16.09 11.49 20.12 11.49 20.12l-1.38-15.82s18.2-4.79 27.8-12.22s14.03-13.79 14.03-13.79s3.24 4.8 13.91 13.67s28.26 12.59 28.26 12.59l.07 15.53s8.46-3.94 9.88-20.07c1.76-20.21-.66-32.3-12.13-45.39");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.oaatlebms {
  fill: var(--svg-color--543930, #543930);
  d: path("m16.53 123.82l1.58-7.48l-13.79 3.44s-.97-13.3 10.9-20.98c13.01-8.42 27.99.55 27.99.55s-1.47 10.04-10.38 18.69c-6 5.81-16.3 5.78-16.3 5.78m94.94 0l-1.58-7.48l13.79 3.44s.97-13.3-10.9-20.98c-13.01-8.42-27.99.55-27.99.55s1.47 10.04 10.38 18.69c6 5.81 16.3 5.78 16.3 5.78");
}

.or_iiybfl {
  cx: 85.6px;
  cy: 80.3px;
  rx: 6.48px;
  ry: 6.71px;
}

.u-2_5vb1m {
  d: path("m111.47 123.82l-1.58-7.48l13.79 3.44s.97-13.3-10.9-20.98c-13.01-8.42-27.99.55-27.99.55s1.47 10.04 10.38 18.69c6 5.81 16.3 5.78 16.3 5.78");
}

.wf7_n7cap {
  fill: var(--svg-color--795548, #795548);
  d: path("M75.01 97.97c-4.19 2.49-17.91 2.49-22.1 0c-2.4-1.43-4.86.76-3.86 2.94c.98 2.15 8.47 7.13 14.95 7.13c6.47 0 13.87-4.98 14.85-7.13c.99-2.19-1.43-4.37-3.84-2.94");
}

.y73_33btq {
  fill: var(--svg-color--404040, #404040);
}

</style>
