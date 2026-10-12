<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="nebgxwxgh"/><path class="yglz_ns6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:capsule" /></template>
<style>
.nebgxwxgh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 16h6.5v2a3.25 3.25 0 0 1-6.5 0Zm2.44-9.12l1-1.74a3.25 3.25 0 0 1 5.62 3.25l-1 1.74Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yglz_ns6f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.25h.01m2.99 1h.01M11 13.5h.01");
}

</style>
