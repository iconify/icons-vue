<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rcpi8-yjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-words-16-filled" /></template>
<style>
.rcpi8-yjr {
  fill: currentColor;
  d: path("M8 3a4 4 0 0 0-3.97 3.507A3.25 3.25 0 0 0 4.25 13h7.5a3.25 3.25 0 0 0 .22-6.493A4 4 0 0 0 8 3M7 6h2a.5.5 0 0 1 0 1H7a.5.5 0 0 1 0-1M4 9.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5M9.5 9h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1");
}

</style>
