<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="atelugguy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:empty-folder-cleaner" /></template>
<style>
.atelugguy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.196 5.5L5.632 7.987l18.024 17.907l-4.822 4.898L30.62 42.5l11.748-12.091l-11.94-11.708l-4.285 4.476z");
}

</style>
