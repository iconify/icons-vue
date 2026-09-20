<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2ywsdvii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crop-16-regular" /></template>
<style>
.c2ywsdvii {
  fill: currentColor;
  d: path("M5 1.5a.5.5 0 0 0-1 0V4H1.5a.5.5 0 0 0 0 1H4v4.5A2.5 2.5 0 0 0 6.5 12H11v2.5a.5.5 0 0 0 1 0V12h2.5a.5.5 0 0 0 0-1h-8A1.5 1.5 0 0 1 5 9.5zm6 5V10h1V6.5A2.5 2.5 0 0 0 9.5 4H6v1h3.5A1.5 1.5 0 0 1 11 6.5");
}

</style>
