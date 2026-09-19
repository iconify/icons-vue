<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y7himrbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linksheet" /></template>
<style>
.y7himrbyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.253 23.954l14.475.037m-11.096 8.69h-6.96a8.681 8.681 0 1 1 0-17.362h6.644m8.034 0h6.96a8.681 8.681 0 1 1 0 17.362h-6.645");
}

</style>
