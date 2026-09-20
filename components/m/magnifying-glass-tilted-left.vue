<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cg2vcqbbw"/><path class="uwpy34ooo"/><path class="r1ql6jb3o"/><path class="b2hnl1j7s"/><path class="sq51zy-7o"/><ellipse transform="rotate(-45 117.005 116.309)" class="j4bla1b7d"/><linearGradient id="SVG13TQfv6S" x1="20.385" x2="36.781" y1="18.024" y2="44.616" gradientUnits="userSpaceOnUse"><stop offset=".285" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><path fill="url(#SVG13TQfv6S)" class="q3ju-1bno"/><path class="nhtw5ugci"/><linearGradient id="SVGOn5qvdRC" x1="58.951" x2="63.085" y1="95.509" y2="52.792" gradientUnits="userSpaceOnUse"><stop offset=".285" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><path fill="url(#SVGOn5qvdRC)" class="gm03xebql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:magnifying-glass-tilted-left" /></template>
<style>
.b2hnl1j7s {
  fill: var(--svg-color--616161, #616161);
  d: path("M88.5 76.96c-1.13-.9-5.05-3-9.36 1.28c-4.3 4.28-2.55 7.66-1.7 8.91c0 0 30.53 33.87 31.92 35.27c2.05 2.05 6.26.3 10.16-3.6s5.78-7.67 3.58-9.87c-1.79-1.79-33.47-31.09-34.6-31.99");
}

.cg2vcqbbw {
  fill: var(--svg-color--81d4fa, #81d4fa);
  d: path("M47.63 12.67c19.85 0 34.8 14.95 34.8 34.8s-16.15 36.01-36 36.01s-34.8-14.95-34.8-34.8s16.15-36.01 36-36.01");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.gm03xebql {
  d: path("M55.92 73.93c-4.45.81-5.77-1.05-5.21-2.9c.44-1.47 2.08-2.1 3.55-2.54c7.84-2.35 14.46-8.84 19.27-15.28c.11 5.59-1.36 8.83-4.05 12.15c-2.63 3.23-6.72 7.32-13.56 8.57");
}

.j4bla1b7d {
  cx: 117.01px;
  cy: 116.31px;
  fill: var(--svg-color--424242, #424242);
  rx: 9.25px;
  ry: 3.56px;
}

.nhtw5ugci {
  fill: var(--svg-color--fff, #fff);
  d: path("M64.05 75.78c0-.46.22-.88.59-1.15c1.95-1.39 7.2-4.64 11.73-13.28C79 56.31 80 52.11 80.28 50.61c.79-4.24 3.01-2.82 2.7-.08c-.36 3.12-3.07 16.85-16.68 26.38c-.95.67-2.25.03-2.25-1.13M26.39 11.39c-.13 1.3-2.34 2.53-2.73 2.78c-2.02 1.3-7.02 3.85-11.59 12.47c-2.13 4.01-3.66 8.14-4.18 10.19c-.85 3.35-3.14 2.68-2.7-.05c.5-3.1 3.85-16.69 17.88-25.58c.99-.62 3.49-1.53 3.32.19");
  opacity: var(--svg-opacity--0-59, 0.59);
}

.q3ju-1bno {
  d: path("M26.52 23.6c-6.52 6.83-9.08 14.39-9.14 22.79c-.02 3.09.41 6.36 2.32 8.78s5.7 3.57 8.2 1.76c1.66-1.2 2.35-3.29 3.16-5.16c1.24-2.87 2.97-5.54 5.1-7.84c2.66-2.88 5.92-5.18 8.46-8.16s4.35-7.01 3.33-10.8c-1.01-3.71-4.67-6.33-8.48-6.76s-9.19 1.45-12.95 5.39");
}

.r1ql6jb3o {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("m99.78 90.86l-8.33 8.38l-19.62-19.8s-1.66-3.19 1.62-6.47s6.71-1.91 6.71-1.91z");
}

.sq51zy-7o {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M43.92 8.64c19.85 0 36 16.15 36 36s-16.15 36-36 36s-36-16.15-36-36s16.15-36 36-36m0-3.96c-22.06 0-39.95 17.89-39.95 39.95s17.89 39.95 39.95 39.95S83.87 66.7 83.87 44.63S65.98 4.68 43.92 4.68");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.uwpy34ooo {
  fill: var(--svg-color--616161, #616161);
  d: path("M47.63 12.67c19.85 0 34.8 14.95 34.8 34.8s-16.15 36.01-36 36.01s-34.8-14.95-34.8-34.8s16.15-36.01 36-36.01m-29.61 4.1C-1.66 36.45 8 65.2 15.69 73.05c14.23 14.52 40.83 22.79 60.73 2.88c18.43-18.43 11.81-41.8-1.17-56.09c-8.62-9.48-37.56-22.74-57.23-3.07");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
