<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rax9y2edg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-split-outline" /></template>
<style>
.rax9y2edg {
  fill: currentColor;
  d: path("M11 20v-7.6l-5-5V10H4V4h6v2H7.4l5.6 5.6V20zm3.85-9.4L13.4 9.15L16.6 6H14V4h6v6h-2V7.4z");
}

</style>
