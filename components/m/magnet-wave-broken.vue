<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tnmk1ibpo"/><path class="p38ldjuia"/><path class="nutxvywlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-wave-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nutxvywlz {
  d: path("M19.5 9C19.5 9 20 9.9 20 12C20 14.1 19.5 15 19.5 15");
}

.p38ldjuia {
  d: path("M21.5 6C21.5 6 23 7.8 23 12C23 16.2 21.5 18 21.5 18");
}

.tnmk1ibpo {
  stroke-linejoin: round;
  d: path("M14.4444 3H16.5C17.3284 3 18 3.67157 18 4.5V6C18 6.82843 17.3284 7.5 16.5 7.5H14.4444M14.4444 3H11C9.51236 3 8.10903 3.36093 6.87279 4M14.4444 3V7.5M14.4444 7.5H10.9444C8.45916 7.5 6.44444 9.51472 6.44444 12C6.44444 13.1525 6.87772 14.2039 7.59028 15M14.4444 16.5H16.5C17.3284 16.5 18 17.1716 18 18V19.5C18 20.3284 17.3284 21 16.5 21H14.4444M14.4444 16.5H10.9444M14.4444 16.5V21M14.4444 21H11C6.02944 21 2 16.9706 2 12C2 10.1499 2.55827 8.4301 3.51555 7");
}

</style>
