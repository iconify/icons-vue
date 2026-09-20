<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7n5sub8u"/><path class="y76ujzb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apna" /></template>
<style>
.c7n5sub8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-33 31h37m-24.667 0v6m12.334-6v6");
}

.y76ujzb4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.215 23.125a2.5 2.5 0 0 1-5 0V21.5a2.5 2.5 0 0 1 5 0m0 4.125V19m22.57 4.125a2.5 2.5 0 0 1-5 0V21.5a2.5 2.5 0 0 1 5 0m0 4.125V19m-7.441 6.625V21.5a2.5 2.5 0 0 0-5 0m-.001 4.125V19m-7.555 4.125a2.5 2.5 0 0 0 5 0V21.5a2.5 2.5 0 0 0-5 0m0-2.5v10");
}

</style>
