<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_be7nb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coins-fill-round" /></template>
<style>
.j_be7nb9d {
  fill: currentColor;
  d: path("M3.472 6.664a6.001 6.001 0 1 1 11.055 4.674A6.001 6.001 0 0 1 3.472 6.664M18.6 10.2a6.001 6.001 0 1 1-8.4 8.4a1 1 0 0 1 .2-1.4a1 1 0 0 1 1.4.2a4 4 0 1 0 5.6-5.6a1 1 0 1 1 1.2-1.6");
}

</style>
