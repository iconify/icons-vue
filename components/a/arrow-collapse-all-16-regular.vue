<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sub0jfbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-collapse-all-16-regular" /></template>
<style>
.sub0jfbkd {
  fill: currentColor;
  d: path("M1 3.5a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1-.5-.5m3.146 2.646a.5.5 0 0 1 .708 0l2 2a.5.5 0 1 1-.708.708L5 7.707V12.5a.5.5 0 0 1-1 0V7.707L2.854 8.854a.5.5 0 1 1-.708-.708zM14.5 6h-6a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1");
}

</style>
