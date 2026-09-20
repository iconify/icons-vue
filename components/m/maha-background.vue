<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGBFX6Nb1N)" class="r4i437pya"/><path class="v04adj8yv"/><path class="rkfsj7_ia"/><path class="ux7i1i6pi"/></g><defs><linearGradient id="SVGBFX6Nb1N" x1="6.953" x2="17.249" y1="17.148" y2="7.056" gradientUnits="userSpaceOnUse"><stop class="jgo7d11uo"/><stop offset=".581" class="iqxmv802c"/><stop offset="1" class="od66jbbkx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:maha-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iqxmv802c {
  stop-color: var(--svg-color--fd3947, #fd3947);
}

.jgo7d11uo {
  stop-color: var(--svg-color--ff8506, #ff8506);
}

.od66jbbkx {
  stop-color: var(--svg-color--fb0078, #fb0078);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rkfsj7_ia {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.499 16.587q-.08 0-.159-.008l-.756 1.063l.571.41l1.382-1.936a1.37 1.37 0 0 1-1.038.471m2.997 0q.08 0 .16-.01l.755 1.064l-.57.411l-1.376-1.934a1.35 1.35 0 0 0 1.031.469");
}

.ux7i1i6pi {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.564 14.864l.44.613l-.67.916l-.44-.595zM10.072 7.04l.434.606l-1.567 2.195l-.547-.441zm1.498 2.089l.428.607L11 11.145l-.547-.444zm1.49-2.082l.431.603l-1.058 1.478l-.431-.603z");
}

.v04adj8yv {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.624 10.83L16.1 5.91a1.35 1.35 0 0 0-1.113-.577c-.445 0-.85.209-1.112.577l-.384.536l-.383-.536a1.35 1.35 0 0 0-1.113-.577c-.446 0-.85.209-1.113.577l-.378.528l-.38-.528a1.36 1.36 0 0 0-1.112-.577c-.444 0-.85.209-1.113.577l-3.524 4.92a2.01 2.01 0 0 0 0 2.34L7.9 18.09a1.36 1.36 0 0 0 1.114.577c.445 0 .85-.209 1.112-.577L12 15.471l.386.541l.004.006l1.485 2.072a1.357 1.357 0 0 0 2.224 0l3.522-4.92a2 2 0 0 0 .003-2.34m-8.178-4.501a.67.67 0 0 1 .55-.285c.22 0 .422.104.551.285l.514.718L12 8.527l-1.065-1.488zm-1.882 11.34a.67.67 0 0 1-.861.21a.7.7 0 0 1-.24-.21L4.94 12.75a1.29 1.29 0 0 1 0-1.502l3.522-4.92a.67.67 0 0 1 .551-.284a.67.67 0 0 1 .55.285l.511.712l-2.713 3.788a2.01 2.01 0 0 0 .001 2.342l.207.284l1.82 2.555c.23.325.574.525.957.568zm1.487-2.075a.674.674 0 0 1-1.101 0l-1.87-2.629h-.003l-.156-.217a1.29 1.29 0 0 1 0-1.502l2.582-3.605l1.064 1.487l-1.216 1.7a2.01 2.01 0 0 0 0 2.341l1.216 1.699zm.95-5.863l1.086 1.516a1.29 1.29 0 0 1 0 1.503L12 14.267l-1.087-1.516a1.29 1.29 0 0 1 0-1.503zm1.648 3.438a2.01 2.01 0 0 0 0-2.342l-1.216-1.7l1.06-1.48l2.577 3.6a1.29 1.29 0 0 1-.002 1.505l-.412.584l-1.604 2.255a.67.67 0 0 1-.551.285a.67.67 0 0 1-.547-.279l-.523-.73zm5.413-.42l-3.523 4.92a.67.67 0 0 1-.55.284a.67.67 0 0 1-.55-.284l-.783-1.091a1.36 1.36 0 0 0 .958-.57l1.378-1.936l.002.002l.226-.32l.264-.373l-.002-.001l.15-.214a2.01 2.01 0 0 0 0-2.341l-2.708-3.778l.514-.719a.67.67 0 0 1 .55-.284c.22 0 .422.103.552.284l3.522 4.92a1.29 1.29 0 0 1 0 1.502");
}

</style>
