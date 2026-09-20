<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xvd8p5lgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:content-view-32-regular" /></template>
<style>
.xvd8p5lgf {
  fill: currentColor;
  d: path("M7.998 11a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-12a2 2 0 0 1-2-2zm14 0h-12v3h12zm-3 7a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2zm0 2h3v2h-3zm-11-1a1 1 0 0 1 1-1h5a1 1 0 1 1 0 2h-5a1 1 0 0 1-1-1m1 3a1 1 0 1 0 0 2h5a1 1 0 1 0 0-2zM8.992 4a5 5 0 0 0-5 5v14a5 5 0 0 0 5 5h14a5 5 0 0 0 5-5V9a5 5 0 0 0-5-5zm-3 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-14a3 3 0 0 1-3-3z");
}

</style>
