<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wl__8ab_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-up-16-regular" /></template>
<style>
.wl__8ab_w {
  fill: currentColor;
  d: path("M7.146 2.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8 3.707V13.5a.5.5 0 0 1-1 0V3.707L4.854 5.854a.5.5 0 1 1-.708-.708z");
}

</style>
