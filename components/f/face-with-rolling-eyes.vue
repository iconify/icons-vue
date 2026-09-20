<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vczuu-btf"/><path class="jh1dobcdu"/><ellipse class="rtyb03bvd"/><defs><ellipse id="SVGs5CqJb9S" class="nzn5n2bqa"/></defs><clipPath id="SVG91pxDeKH"><use href="#SVGs5CqJb9S"/></clipPath><circle clip-path="url(#SVG91pxDeKH)" class="ce3jk-qvw"/><ellipse class="oljnmxtdq"/><defs><ellipse id="SVG8YXNYRop" class="n2508lbnq"/></defs><clipPath id="SVGDrpK1bCi"><use href="#SVG8YXNYRop"/></clipPath><circle clip-path="url(#SVGDrpK1bCi)" class="y_wqfuvac"/><path class="myk5l0n9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:face-with-rolling-eyes" /></template>
<style>
.ce3jk-qvw {
  cx: 83.5px;
  cy: 47px;
  r: 7.9px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.jh1dobcdu {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M75.6 94.8h-24c-1.6 0-2.9-1.5-2.9-3.3s1.3-3.3 2.9-3.3h24c1.6 0 2.9 1.5 2.9 3.3s-1.3 3.3-2.9 3.3");
}

.myk5l0n9i {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M23.6 72h34.2v8.7H23.6zm46.6 0h34.2v8.7H70.2z");
}

.n2508lbnq {
  cx: 40.6px;
  cy: 58.8px;
  rx: 16.6px;
  ry: 16.3px;
}

.nzn5n2bqa {
  cx: 87.4px;
  cy: 58.8px;
  rx: 16.6px;
  ry: 16.3px;
}

.oljnmxtdq {
  cx: 40.6px;
  cy: 58.8px;
  fill: var(--svg-color--fff, #fff);
  rx: 16.6px;
  ry: 16.3px;
}

.rtyb03bvd {
  cx: 87.4px;
  cy: 58.8px;
  fill: var(--svg-color--fff, #fff);
  rx: 16.6px;
  ry: 16.3px;
}

.vczuu-btf {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M63.8 9.5c-62.5 0-64 70.1-64 83.9c0 13.9 28.7 25.1 64 25.1s64-11.2 64-25.1c0-13.8-1.5-83.9-64-83.9");
}

.y_wqfuvac {
  cx: 36.7px;
  cy: 47px;
  r: 7.9px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

</style>
