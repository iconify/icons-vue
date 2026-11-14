<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qzhx9dtag"/><path class="zzhx06bke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-request" /></template>
<style>
.qzhx9dtag {
  d: path("M11.954 20.546L11 21.5L2.5 13L13 2.5h8.5V11l-.99.99M9.5 13.5l4-4M10 10h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zzhx06bke {
  d: path("M15.75 14.75h4.75a1 1 0 0 1 1 1V19a1 1 0 0 1-1 1h-3.25l-2.5 1.75v-6a1 1 0 0 1 1-1Z");
}

</style>
