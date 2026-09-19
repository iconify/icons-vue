<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jw2wqmb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chestnyj-znak" /></template>
<style>
.jw2wqmb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.947 5.5H9.5a4 4 0 0 0-4 4v5.447m37 0V9.5a4 4 0 0 0-4-4h-5.447M5.5 33.053V38.5a4 4 0 0 0 4 4h5.447m18.106 0H38.5a4 4 0 0 0 4-4v-5.447m-27.594-8.637l5.779 5.647l12.409-12.126");
}

</style>
