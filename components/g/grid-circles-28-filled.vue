<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="qt_e4xbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:grid-circles-28-filled" /></template>
<style>
.qt_e4xbfx {
  fill: currentColor;
  d: path("M8 13A5 5 0 1 0 8 3a5 5 0 0 0 0 10m12 0a5 5 0 1 0 0-10a5 5 0 0 0 0 10m-7 7a5 5 0 1 1-10 0a5 5 0 0 1 10 0m7 5a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

</style>
