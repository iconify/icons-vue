<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljoi4gczc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-shape-up-stack-2" /></template>
<style>
.ljoi4gczc {
  fill: currentColor;
  d: path("M9 23v-3H4l8-9l8 9h-5v3zm-5-8l8-9l8 9h-2.675L12 9l-5.325 6zm0-5l8-9l8 9h-2.675L12 4l-5.325 6z");
}

</style>
