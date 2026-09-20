<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bkbfzi14j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:engine-fill" /></template>
<style>
.bkbfzi14j {
  fill: currentColor;
  d: path("M256 120v48a16 16 0 0 1-16 16h-12.69L192 219.31a15.86 15.86 0 0 1-11.31 4.69h-77.38A15.86 15.86 0 0 1 92 219.31L52.69 180A15.86 15.86 0 0 1 48 168.69V148H24v24a8 8 0 0 1-16 0v-64a8 8 0 0 1 16 0v24h24V80a16 16 0 0 1 16-16h60V40h-24a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16h-24v24h40.69A15.86 15.86 0 0 1 192 68.69L227.31 104H240a16 16 0 0 1 16 16");
}

</style>
