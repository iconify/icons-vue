<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGP8ZlhbKI" cx="-2.176" cy="-852.913" r="48.27" gradientTransform="matrix(.36 .402 .222 -.163 205.356 -126.01)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o5tfh3bca"/><stop offset=".3" class="us7-fvb-i"/></radialGradient><radialGradient id="SVG88UyqbDo" cx="4199.973" cy="-1221.763" r="83.239" gradientTransform="matrix(.031 .03 .075 -.062 -25.785 -180.883)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o5tfh3bca"/><stop offset="1" class="us7-fvb-i"/></radialGradient><radialGradient id="SVGJZePkeZl" cx="-264.938" cy="-543.943" r="27.886" gradientTransform="matrix(-1.048 -.5 -1.117 .527 -867.609 176.63)" gradientUnits="userSpaceOnUse"><stop offset="0" class="y6fssjfyp"/><stop offset=".15" class="us7-fvb-i"/></radialGradient><linearGradient id="SVGXUddjV3U" x1="-113.501" x2="-113.501" y1="-375.465" y2="-404.611" gradientTransform="matrix(1 0 0 -1 129.5 -387.5)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs><path class="mm9vosb5q"/><path class="ypib1ctzi"/><path class="zd4pm5c5s"/><path stroke="url(#SVGP8ZlhbKI)" class="flzo8qb5f"/><path stroke="url(#SVG88UyqbDo)" class="s97dv42co"/><path stroke="url(#SVGJZePkeZl)" class="agmfd8bpm"/><path class="d2pe8pyvj"/><path class="o1yg4dbmi"/><path class="tf0hct_st"/><path fill="url(#SVGXUddjV3U)" class="q0ulvpb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-powershell2" /></template>
<style>
.agmfd8bpm {
  fill: none;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--100px, 100px);
  d: path("M8.73 23.121h1.124");
}

.d2pe8pyvj {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.817 24.052a1.226 1.226 0 0 1-.7-2.237c2.77-1.9 6.941-4.786 8.809-6.117c-1.253-1.385-3.8-4.088-5.665-6.046a1.226 1.226 0 1 1 1.78-1.692c.017.017 1.674 1.756 3.3 3.493A219 219 0 0 1 18.61 13.9c.334.368.583.649.76.856a1.51 1.51 0 0 1 .494 1.539c-.165.492-.165.492-5.428 4.142c-2.438 1.691-4.9 3.383-4.926 3.4a1.2 1.2 0 0 1-.693.215");
}

.flzo8qb5f {
  fill: none;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--76-717px, 76.717px);
  d: path("M18.558 15.816c.061-.183-7-7.561-7-7.561");
}

.mm9vosb5q {
  fill: var(--svg-color--2a80c9, #2a80c9);
  d: path("M8.492 5.6h19.843a1.517 1.517 0 0 1 1.546 1.948l-3.923 16.906a2.64 2.64 0 0 1-2.45 1.948H3.665a1.517 1.517 0 0 1-1.546-1.948L6.042 7.545A2.64 2.64 0 0 1 8.492 5.6");
}

.o1yg4dbmi {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.925 23.929h-4.882a1.226 1.226 0 0 1 0-2.453h4.882a1.226 1.226 0 1 1 0 2.453");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.o5tfh3bca {
  stop-color: var(--svg-color--7ce1ff, #7ce1ff);
}

.q0ulvpb4z {
  d: path("M8.492 5.6a2.63 2.63 0 0 0-2.45 1.948L2.118 24.455A1.514 1.514 0 0 0 3.664 26.4h19.843a2.63 2.63 0 0 0 2.45-1.948L29.88 7.545A1.514 1.514 0 0 0 28.334 5.6z");
}

.s97dv42co {
  fill: var(--svg-color--2aa7c9, #2aa7c9);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--76-717px, 76.717px);
  d: path("M8.558 22.835s9.942-6.825 10-7");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tf0hct_st {
  d: path("M28.606 13.04c-10.079.433-19.226 2.533-25.181 5.78l-1.307 5.634A1.514 1.514 0 0 0 3.664 26.4h19.843a2.63 2.63 0 0 0 2.45-1.948l2.648-11.412Z");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.us7-fvb-i {
  stop-color: var(--svg-color--7ce1ff, #7ce1ff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.y6fssjfyp {
  stop-color: var(--svg-color--7ce1ff, #7ce1ff);
  stop-opacity: 0.8;
}

.ypib1ctzi {
  fill: var(--svg-color--1f5e93, #1f5e93);
  d: path("M23.508 26.471H3.665a1.65 1.65 0 0 1-1.333-.6a1.66 1.66 0 0 1-.279-1.436L5.976 7.53a2.71 2.71 0 0 1 2.516-2h19.843a1.584 1.584 0 0 1 1.612 2.031L26.024 24.47a2.71 2.71 0 0 1-2.516 2.001M8.492 5.664a2.57 2.57 0 0 0-2.384 1.9L2.185 24.47a1.53 1.53 0 0 0 .253 1.321a1.52 1.52 0 0 0 1.227.544h19.843a2.57 2.57 0 0 0 2.384-1.9L29.815 7.53a1.45 1.45 0 0 0-1.48-1.866Z");
  opacity: var(--svg-opacity--0-945, 0.945);
}

.zd4pm5c5s {
  fill: var(--svg-color--bbd8f1, #bbd8f1);
  d: path("M23.541 26.359H3.7a1.57 1.57 0 0 1-1.267-.559a1.57 1.57 0 0 1-.263-1.364L6.093 7.522a2.514 2.514 0 0 1 2.366-1.881H28.3a1.5 1.5 0 0 1 1.53 1.927l-3.923 16.909a2.514 2.514 0 0 1-2.366 1.882M8.459 5.843A2.34 2.34 0 0 0 6.29 7.568L2.367 24.477a1.38 1.38 0 0 0 .224 1.192a1.37 1.37 0 0 0 1.107.487h19.843a2.34 2.34 0 0 0 2.168-1.725l3.924-16.909A1.3 1.3 0 0 0 28.3 5.843Z");
  opacity: var(--svg-opacity--0-945, 0.945);
}

</style>
