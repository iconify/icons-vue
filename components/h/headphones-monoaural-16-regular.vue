<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bo_ua7ubz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-monoaural-16-regular" /></template>
<style>
.bo_ua7ubz {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7v4.5a2.5 2.5 0 0 1-2.5 2.5h-2a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 .5-.5H14V8A6 6 0 0 0 2.173 6.58a.54.54 0 0 1-.515.42a.475.475 0 0 1-.477-.574A7 7 0 0 1 8 1m3 13h1.5a1.5 1.5 0 0 0 1.5-1.5V10h-3z");
}

</style>
