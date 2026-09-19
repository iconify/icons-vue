<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r1hyp9pns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hojskolesangbogen" /></template>
<style>
.r1hyp9pns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M17.375 14v20m13.25-20v20m-13.25-10.038h13.25M29.375 14h2.5m-15.75 0h2.5m10.75 20h2.5m-15.75 0h2.5");
}

</style>
