<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lu984o99d"/><circle class="jjujtozoj"/><circle class="xr5jvhb8o"/><circle class="x_lu7cskq"/><circle class="labf3rbto"/><circle class="hu582dbev"/><circle class="tlh-c5zho"/><circle class="hl4uf-enw"/><circle class="iageydb9p"/><circle class="ypxpawbtf"/><circle class="w-nlq19ba"/><circle class="xrhb2_fqk"/><circle class="posxynkzs"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:claude" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hl4uf-enw {
  cx: 37.348px;
  cy: 35.947px;
  r: 0.75px;
  fill: currentColor;
}

.hu582dbev {
  cx: 41.193px;
  cy: 21.712px;
  r: 0.75px;
  fill: currentColor;
}

.iageydb9p {
  cx: 33.064px;
  cy: 38.987px;
  r: 0.75px;
  fill: currentColor;
}

.jjujtozoj {
  cx: 9.652px;
  cy: 14.182px;
  r: 0.75px;
  fill: currentColor;
}

.labf3rbto {
  cx: 35.97px;
  cy: 11.263px;
  r: 0.75px;
  fill: currentColor;
}

.lu984o99d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.956 24.475L9.652 14.182m14.304 10.293L15.763 7.299m8.193 17.176l3.233-16.747m-3.233 16.747L35.97 11.263M23.956 24.475l17.237-2.764m-17.237 2.764l17.353 3.839m-17.353-3.839l13.392 11.472M23.956 24.475l9.108 14.512m-9.108-14.512l-.849 16.262m.849-16.262l-9.178 14.343m9.178-14.343l-13.15 8.935m13.15-8.935l-17.23-1.19");
}

.posxynkzs {
  cx: 6.726px;
  cy: 23.285px;
  r: 0.75px;
  fill: currentColor;
}

.tlh-c5zho {
  cx: 41.309px;
  cy: 28.313px;
  r: 0.75px;
  fill: currentColor;
}

.w-nlq19ba {
  cx: 14.778px;
  cy: 38.818px;
  r: 0.75px;
  fill: currentColor;
}

.x_lu7cskq {
  cx: 27.189px;
  cy: 7.728px;
  r: 0.75px;
  fill: currentColor;
}

.xr5jvhb8o {
  cx: 15.762px;
  cy: 7.299px;
  r: 0.75px;
  fill: currentColor;
}

.xrhb2_fqk {
  cx: 10.806px;
  cy: 33.41px;
  r: 0.75px;
  fill: currentColor;
}

.ypxpawbtf {
  cx: 23.107px;
  cy: 40.736px;
  r: 0.75px;
  fill: currentColor;
}

</style>
