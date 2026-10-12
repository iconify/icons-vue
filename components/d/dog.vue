<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ygbs1zb2c"/><path class="mcud9rb4g"/><path class="wexmdqbpo"/><path class="cg550_ipx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dog" /></template>
<style>
.cg550_ipx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 14.75h2.5L12 16.25Zm1.25 1.5v1.5");
}

.mcud9rb4g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.6 6.7c-2.6-1.2-4.85.8-4.85 3.55c0 1.75.5 3.25 1.5 4c.75.6 1.5.5 1.75-.25m10.4-7.3c2.6-1.2 4.85.8 4.85 3.55c0 1.75-.5 3.25-1.5 4c-.75.6-1.5.5-1.75-.25");
}

.wexmdqbpo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 11.5h.01m3.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ygbs1zb2c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5c3.75 0 6 2.5 6 6.25v3.5c0 3.5-2.5 6-6 6s-6-2.5-6-6v-3.5C6 7.5 8.25 5 12 5");
}

</style>
