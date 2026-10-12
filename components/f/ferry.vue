<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="go_n_u8az"/><path class="s9xtj-b_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ferry" /></template>
<style>
.go_n_u8az {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8.75V5.5h3v3.25M5.75 13.5V9.75a1 1 0 0 1 1-1h10.5a1 1 0 0 1 1 1v3.75Zm-3 0h18.5l-1.6 4a1.75 1.75 0 0 1-1.62 1.1H5.97a1.75 1.75 0 0 1-1.62-1.1Z");
}

.s9xtj-b_d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 11.25h.01m3.49 0h.01m3.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
