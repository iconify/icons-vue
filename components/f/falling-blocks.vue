<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v5plj6b3f"/><path class="ayao-pqrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:falling-blocks" /></template>
<style>
.ayao-pqrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.012 24.472l-18.493-8.23a2 2 0 0 1-1.014-2.64L26.111 5.5M5.628 38.403L21.1 35.116a2 2 0 0 0 1.54-2.372l-5.778-27.2");
}

.v5plj6b3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M18.658 35.634l13.523 6.774");
}

</style>
