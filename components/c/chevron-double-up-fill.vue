<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v--1l_lzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-up-fill" /></template>
<style>
.v--1l_lzp {
  fill: currentColor;
  d: path("m12 8.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414l4-4a.997.997 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Zm0 6l-3.293 3.293a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

</style>
