<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrje8sbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contrast-square-sharp" /></template>
<style>
.lrje8sbpu {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5zm.5-10h2v2H9V9h2V7.5H9v-2H7.5v2h-2zm11.525 7h-5v-1.5h5z");
}

</style>
