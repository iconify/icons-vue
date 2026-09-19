<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qa7x_3bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:austrianairlines" /></template>
<style>
.qa7x_3bda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.5 34.108l6.906-.938C22.796 22.617 31.418 19.207 44.5 13.892c-10.373 0-26.828 2.236-37.125 5.495l5.901 1.335q3.032-1.553 5.618-1.847c1.108 1.847-7.323 9.596-15.394 15.233");
}

</style>
