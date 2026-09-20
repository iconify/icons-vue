<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egtr3x30v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-axis-outline-sharp" /></template>
<style>
.egtr3x30v {
  fill: currentColor;
  d: path("M3.5 19L2 17.5L9.5 10l4 4l1.675-1.9l-5.6-5.175L3.5 13L2 11.5L9.5 4l7.1 6.525L20.6 6L22 7.4l-3.95 4.45L22 15.5L20.5 17l-3.85-3.55L13.5 17l-4-4z");
}

</style>
