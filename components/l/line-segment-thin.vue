<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m3dytkbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:line-segment-thin" /></template>
<style>
.m3dytkbpp {
  fill: currentColor;
  d: path("M211.81 44.19a28 28 0 0 0-42.23 36.57l-88.82 88.82a28 28 0 0 0-36.57 2.63a28 28 0 1 0 42.23 3l88.82-88.82a28 28 0 0 0 36.57-42.23Zm-133.67 162a20 20 0 1 1 0-28.28a20 20 0 0 1 0 28.24Zm128-128a20 20 0 0 1-28.28 0a20 20 0 1 1 28.28 0");
}

</style>
