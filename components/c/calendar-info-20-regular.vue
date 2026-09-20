<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p5cd-2faq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-info-20-regular" /></template>
<style>
.p5cd-2faq {
  fill: currentColor;
  d: path("M14.5 3A2.5 2.5 0 0 1 17 5.5v4.1a5.5 5.5 0 0 0-1-.393V7H4v7.5A1.5 1.5 0 0 0 5.5 16h3.707q.149.524.393 1H5.5A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3zm0 1h-9A1.5 1.5 0 0 0 4 5.5V6h12v-.5A1.5 1.5 0 0 0 14.5 4m-.625 8.5a.625.625 0 1 1 1.25 0a.625.625 0 0 1-1.25 0m1.125 4a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 1 0zm-5-2a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0m1 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0");
}

</style>
