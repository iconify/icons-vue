<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c58z1pbtt"/><path class="kzykk8swa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-samsung-18" /></template>
<style>
.c58z1pbtt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.28 22.2l4-2.2m0 0v16m12.225-8h-2.6c-2.2 0-4 1.8-4 4s1.8 4 4 4h2.6c2.2 0 4-1.8 4-4s-1.8-4-4-4m0 0c2.2 0 4-1.8 4-4s-1.8-4-4-4h-2.6c-2.2 0-4 1.8-4 4s1.8 4 4 4");
}

.kzykk8swa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-4v1a3.5 3.5 0 1 1-7 0v-1h-8v1a3.5 3.5 0 1 1-7 0v-1h-3a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
