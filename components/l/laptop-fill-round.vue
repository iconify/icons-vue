<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjgx2qbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-fill-round" /></template>
<style>
.gjgx2qbcs {
  fill: currentColor;
  d: path("M4 15.171V8a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v7.171A3.001 3.001 0 0 1 19 21H5a3 3 0 0 1-1-5.829M5 17a1 1 0 0 0 0 2h14a1 1 0 0 0 0-2Z");
}

</style>
