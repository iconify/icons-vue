<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nx4172vrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sync-circle-16-filled" /></template>
<style>
.nx4172vrq {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1M5 8a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-.848a2.994 2.994 0 0 0 4.9.148a.5.5 0 1 0-.798-.6A2 2 0 0 1 6.27 9H7a.5.5 0 0 0 0-1zm6-3a.5.5 0 0 0-.5.5v.845a2.997 2.997 0 0 0-4.9-.146a.5.5 0 0 0 .8.602A1.997 1.997 0 0 1 9.732 7H9a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5v-2A.5.5 0 0 0 11 5");
}

</style>
