<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dree-b_ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:algemeen-dagblad" /></template>
<style>
.dree-b_ne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.524 36.813h5.765c6.192 0 11.211-5.02 11.211-11.211v-3.204c0-6.191-5.02-11.21-11.21-11.21h-9.414v17.136m0 0H8.148M4.5 36.813l11.012-25.625l11.011 25.625");
}

</style>
