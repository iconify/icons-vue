<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="az0nhqcow"/><path class="lbxv7ysiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:confetti-burst" /></template>
<style>
.az0nhqcow {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.54 8.01l-2.25-.83q-.47-.17-.3-.64l.83-2.25q.17-.47.64-.3l2.25.83q.47.17.3.64l-.83 2.25q-.17.47-.64.3m13.27 9.52l-2.18 1.02q-.45.21-.66-.24l-1.02-2.18q-.21-.45.24-.66l2.18-1.02q.45-.21.66.24l1.02 2.18q.21.45-.24.66M7 19.21L5.73 17.7q-.32-.38.06-.7l1.51-1.27q.38-.32.7.06l1.27 1.51q.32.38-.06.7L7.7 19.27q-.38.32-.7-.06m6-13.46c1-1.25 2-.25 3-1.25s2 .25 3-1M3.5 12.25c1.25-1 2.25.25 3.25-.75s2 .25 3.25-.5m3.25 1.5c1 1.25 2.25.5 3 1.75");
}

.lbxv7ysiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.5 9h.01M13 20h.01M11.25 8.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
