<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qrxti759m"/><path class="qfuru8v5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-phone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qfuru8v5p {
  d: path("M12.5 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4.75 16c0 3.5 1.75 5.5 4.25 5.5c2 0 3-.75 3.5-2");
}

.qrxti759m {
  d: path("M12 2.5h5A3.5 3.5 0 0 1 20.5 6v10a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 8.5 16V6A3.5 3.5 0 0 1 12 2.5M4.75 5zA1.75 1.75 0 0 1 6.5 6.75v7.5A1.75 1.75 0 0 1 4.75 16A1.75 1.75 0 0 1 3 14.25v-7.5A1.75 1.75 0 0 1 4.75 5m6.75 1.5h6");
}

</style>
