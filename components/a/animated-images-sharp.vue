<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3y2-bczb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:animated-images-sharp" /></template>
<style>
.d3y2-bczb {
  fill: currentColor;
  d: path("m12 13.5l6-4l-6-4zm-8.3 8.625L1.85 7.2L5 6.85V19h13.3l.125 1.325zM7 17V2h15v15z");
}

</style>
