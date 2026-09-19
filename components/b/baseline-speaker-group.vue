<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz-edsg6y"/><circle class="tbb72rihx"/><path class="vk1e_ukdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-speaker-group" /></template>
<style>
.tbb72rihx {
  cx: 14px;
  cy: 12.5px;
  r: 2.5px;
  fill: currentColor;
}

.uz-edsg6y {
  fill: currentColor;
  d: path("M18.2 1H9.8C8.81 1 8 1.81 8 2.8v14.4c0 .99.81 1.79 1.8 1.79l8.4.01c.99 0 1.8-.81 1.8-1.8V2.8c0-.99-.81-1.8-1.8-1.8M14 3c1.1 0 2 .89 2 2s-.9 2-2 2s-2-.89-2-2s.9-2 2-2m0 13.5c-2.21 0-4-1.79-4-4s1.79-4 4-4s4 1.79 4 4s-1.79 4-4 4");
}

.vk1e_ukdu {
  fill: currentColor;
  d: path("M6 5H4v16a2 2 0 0 0 2 2h10v-2H6z");
}

</style>
