<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v2-2ehscz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-repeat-all-32-light" /></template>
<style>
.v2-2ehscz {
  fill: currentColor;
  d: path("M26.96 9.937a.48.48 0 0 1 .695.006A9 9 0 0 1 21 25H9.707l4.147 4.147a.5.5 0 1 1-.707.707l-5-5a.5.5 0 0 1 0-.707l5-5a.5.5 0 1 1 .707.707L9.707 24H21a8 8 0 0 0 5.953-13.343a.525.525 0 0 1 .008-.72m-8.814-7.79a.5.5 0 0 1 .707 0l5 5a.5.5 0 0 1 0 .707l-5 5a.5.5 0 1 1-.707-.707L22.294 8H11a8 8 0 0 0-5.954 13.342a.525.525 0 0 1-.008.72a.48.48 0 0 1-.694-.006A9 9 0 0 1 11 7h11.293l-4.146-4.146a.5.5 0 0 1 0-.708");
}

</style>
