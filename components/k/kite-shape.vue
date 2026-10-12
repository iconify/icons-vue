<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pjb072b8m"/><path class="zrnuaslnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kite-shape" /></template>
<style>
.pjb072b8m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.53 3.79l4.69 3.92q1.53 1.29.48 2.99l-5.65 9.1q-1.05 1.7-2.1 0L5.3 10.7Q4.25 9 5.78 7.71l4.69-3.92q1.53-1.29 3.06 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zrnuaslnh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.5h.01");
}

</style>
