<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uptxvgbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-16-filled" /></template>
<style>
.uptxvgbss {
  fill: currentColor;
  d: path("M2.727 12.07a1.75 1.75 0 0 0 1.236.118l2.4-.656a3.16 3.16 0 0 0 1.4-.816L8.479 10H13.5a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 1 13.5v-2a1.5 1.5 0 0 1 .78-1.316a1.75 1.75 0 0 0 .947 1.885M11.082 1a1.9 1.9 0 0 0-1.356.562L4.168 7.12a1.9 1.9 0 0 0-.494.849l-.656 2.4a.5.5 0 0 0 .614.613l2.4-.656a1.9 1.9 0 0 0 .849-.494l5.558-5.558A1.919 1.919 0 0 0 11.082 1");
}

</style>
