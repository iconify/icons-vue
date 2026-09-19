<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffwxk9l8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-bluetooth" /></template>
<style>
.ffwxk9l8j {
  fill: currentColor;
  d: path("M17.71 7.71L12 2h-1v7.59L6.41 5L5 6.41L10.59 12L5 17.59L6.41 19L11 14.41V22h1l5.71-5.71l-4.3-4.29zM13 5.83l1.88 1.88L13 9.59zm1.88 10.46L13 18.17v-3.76z");
}

</style>
