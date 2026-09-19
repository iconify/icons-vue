<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx6imsemk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-u-turn-left" /></template>
<style>
.zx6imsemk {
  fill: currentColor;
  d: path("M18 9v12h-2V9c0-2.21-1.79-4-4-4S8 6.79 8 9v4.17l1.59-1.59L11 13l-4 4l-4-4l1.41-1.41L6 13.17V9c0-3.31 2.69-6 6-6s6 2.69 6 6");
}

</style>
