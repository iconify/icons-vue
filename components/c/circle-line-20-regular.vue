<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bvoij5btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-line-20-regular" /></template>
<style>
.bvoij5btx {
  fill: currentColor;
  d: path("M3.018 9.5h13.964a7 7 0 0 0-13.964 0M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m14.982.5H3.018a7 7 0 0 0 13.964 0");
}

</style>
