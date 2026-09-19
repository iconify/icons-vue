<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="psocidfhi"/><path class="c70lsdb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:artecture" /></template>
<style>
.c70lsdb9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.79 29.304H6.735V5.5h34.53v23.804H38.21m-7.463 2.184L37.584 42.5h3.629l-6.097-11.012M24 9.271l-7.696 16.44M24 9.271l7.696 16.44");
}

.psocidfhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.79 28.936v2.552h28.42v-2.552zm7.463 2.552L10.416 42.5H6.787l6.097-11.012");
}

</style>
