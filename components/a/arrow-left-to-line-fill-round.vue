<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3n38s0_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-to-line-fill-round" /></template>
<style>
.n3n38s0_m {
  fill: currentColor;
  d: path("M5 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0m7.707 2.707L10.414 11H20a1 1 0 0 1 0 2h-9.586l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a.997.997 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414");
}

</style>
