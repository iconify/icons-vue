<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect transform="rotate(-45 20.21 24)" class="oxmu-p53m"/><rect transform="rotate(-45 24 24)" class="sfg538brk"/><rect transform="rotate(-45 27.79 24)" class="f_uwj6bau"/><path class="akp8gcd1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lifevit" /></template>
<style>
.akp8gcd1j {
  d: path("M11.55 24.073h7.037l4.385 4.484l3.194-8.815l3.766 4.33h6.519");
}

.f_uwj6bau {
  width: 24.901px;
  height: 24.901px;
  x: 15.339px;
  y: 11.55px;
  rx: 2.165px;
  ry: 2.165px;
}

.oxmu-p53m {
  width: 24.901px;
  height: 24.901px;
  x: 7.76px;
  y: 11.55px;
  rx: 2.165px;
  ry: 2.165px;
}

.sfg538brk {
  width: 24.901px;
  height: 24.901px;
  x: 11.55px;
  y: 11.55px;
  rx: 2.165px;
  ry: 2.165px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
