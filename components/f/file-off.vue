<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn68455at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-off" /></template>
<style>
.tn68455at {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H7M5 7v12a2 2 0 0 0 2 2h10c.552 0 1.052-.224 1.414-.586M19 15V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4M2 4l18 18");
}

</style>
