<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="waezb5bcd"/><path class="f69v2pg5j"/><path class="vx3arhblv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ghost-face" /></template>
<style>
.f69v2pg5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 9.25h.01m4.99 0h.01");
}

.vx3arhblv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0");
}

.waezb5bcd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a7 7 0 0 1 7 7v4.5c0 2 .75 3.5 2 4.5c-1.75 1-3.75.75-5-.25c-1 1.5-2.5 2.25-4 2.25c-4 0-7-3-7-7v-4a7 7 0 0 1 7-7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
