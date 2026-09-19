<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ccuwv498z"/><path class="t5qpj2b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bondex" /></template>
<style>
.ccuwv498z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.546 15.778L31.224 5.5l-8.257 8.222l18.579 18.5L31.224 42.5l-8.257-8.222zm-18.579-2.056L6.454 30.166");
}

.t5qpj2b6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.225 5.5H6.455v37h24.77m-8.258-8.222L12.645 24");
}

</style>
