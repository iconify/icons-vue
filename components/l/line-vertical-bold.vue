<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kp91cnxcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:line-vertical-bold" /></template>
<style>
.kp91cnxcc {
  fill: currentColor;
  d: path("M140 24v208a12 12 0 0 1-24 0V24a12 12 0 0 1 24 0");
}

</style>
