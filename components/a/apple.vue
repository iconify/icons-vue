<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="otm3d-b1p"/><path class="lio5ymbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:apple" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lio5ymbxc {
  d: path("M12 8c0-1.75.4-3.25 1.25-4.5m1.5 1.75c.4-1.5 1.6-2.4 3.5-2.5c-.25 1.6-1.5 2.5-3.5 2.5m-8 7.25c0-1.4.6-2.4 1.75-2.85");
}

.otm3d-b1p {
  d: path("M12 8c-1.2-.6-2.6-.5-3.9-.5c-2.8 0-4.85 2.4-4.85 5.9c0 4.4 2.85 7.85 5.35 7.85c1.2 0 1.9-.6 3.4-.6s2.2.6 3.4.6c2.5 0 5.35-4.2 5.35-7.85c0-3.5-2.05-5.9-4.85-5.9c-1.3 0-2.7-.1-3.9.5");
}

</style>
