<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ygalvrb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crystal-para-samsung-internet" /></template>
<style>
.ygalvrb-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.75 14.25L24 4.5l-9.75 9.75v19.5L24 43.5l9.75-9.75z");
}

</style>
