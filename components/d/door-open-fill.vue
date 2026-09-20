<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w373lybhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:door-open-fill" /></template>
<style>
.w373lybhq {
  fill: currentColor;
  d: path("M232 216h-24V40a16 16 0 0 0-16-16H64a16 16 0 0 0-16 16v176H24a8 8 0 0 0 0 16h208a8 8 0 0 0 0-16m-64 0H64V40h104Zm-40-84a12 12 0 1 1 12 12a12 12 0 0 1-12-12");
}

</style>
