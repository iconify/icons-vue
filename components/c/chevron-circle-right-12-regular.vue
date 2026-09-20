<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gib8wmbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-12-regular" /></template>
<style>
.gib8wmbbz {
  fill: currentColor;
  d: path("M5.854 4.146a.5.5 0 1 0-.708.708L6.293 6L5.146 7.146a.5.5 0 1 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708zM6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1M2 6a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>
