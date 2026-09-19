<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="plk5clgsr"/><path class="kzykk8swa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-samsung-15" /></template>
<style>
.kzykk8swa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-4v1a3.5 3.5 0 1 1-7 0v-1h-8v1a3.5 3.5 0 1 1-7 0v-1h-3a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.plk5clgsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.28 22.2l4-2.2m0 0v16m6.025-1.35c1.104.926 2.176 1.35 4.854 1.35h.46a4.485 4.485 0 0 0 4.486-4.485h0a4.486 4.486 0 0 0-4.486-4.486h-5.314V20h9.8");
}

</style>
