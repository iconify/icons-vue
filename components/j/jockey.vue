<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ex3y4gbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jockey" /></template>
<style>
.ex3y4gbii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.088 4.5h15.08l-.029 27.892C30.133 38.717 25.31 43.5 19.348 43.5S8.585 38.717 8.585 32.776s4.8-10.724 10.763-10.724h7.008m7.596 0h5.463");
}

</style>
