<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqr4u5fku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-play-disabled" /></template>
<style>
.sqr4u5fku {
  fill: currentColor;
  d: path("M8 5.19V5l11 7l-2.55 1.63zm12 14.54l-5.11-5.11L8 7.73L4.27 4L3 5.27l5 5V19l5.33-3.4l5.4 5.4z");
}

</style>
