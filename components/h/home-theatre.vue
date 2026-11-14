<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybcs8elwr"/><path class="ro31xebxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-theatre" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ro31xebxf {
  d: path("M4.5 17.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0m13 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.ybcs8elwr {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6A3.5 3.5 0 0 1 18 9.5H6A3.5 3.5 0 0 1 2.5 6A3.5 3.5 0 0 1 6 2.5m-.875 9.75h.75A2.625 2.625 0 0 1 8.5 14.875v4A2.625 2.625 0 0 1 5.875 21.5h-.75A2.625 2.625 0 0 1 2.5 18.875v-4a2.625 2.625 0 0 1 2.625-2.625m13 0h.75a2.625 2.625 0 0 1 2.625 2.625v4a2.625 2.625 0 0 1-2.625 2.625h-.75a2.625 2.625 0 0 1-2.625-2.625v-4a2.625 2.625 0 0 1 2.625-2.625M12 9.5v3m-1.5 0h3");
}

</style>
