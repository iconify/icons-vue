<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm5j7xbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sync-corner-alt" /></template>
<style>
.qm5j7xbks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19A5 5 0 0 1 7 9c1.819-6.366 9.428-6.115 10.79 0M21 19a4.472 4.472 0 0 1-8 0m3 0h-3v3m0-7a4.472 4.472 0 0 1 8 0m-3 0h3v-3");
}

</style>
