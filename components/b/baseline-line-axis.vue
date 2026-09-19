<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj97gm9bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-line-axis" /></template>
<style>
.hj97gm9bh {
  fill: currentColor;
  d: path("m22 7.43l-1.41-1.41l-4.03 4.53L9.5 4L2 11.51l1.5 1.5l6.14-6.15l5.59 5.18l-1.73 1.95l-4-4L2 17.5L3.5 19l6-6.01l4 4l3.19-3.59l3.9 3.61L22 15.6l-3.98-3.7z");
}

</style>
