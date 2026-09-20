<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vuw2z3b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-image-20-filled" /></template>
<style>
.vuw2z3b4r {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v6A2.5 2.5 0 0 0 4.5 13H7v-2.5A3.5 3.5 0 0 1 10.5 7H14V4.5A2.5 2.5 0 0 0 11.5 2zm0 2a.5.5 0 0 1 .5.5V5a.5.5 0 0 1-1 0v-.5a.5.5 0 0 1 .5-.5m7.5.5V5a.5.5 0 0 1-1 0v-.5a.5.5 0 0 1 1 0M4.5 6.75a.5.5 0 0 1 .5.5v.5a.5.5 0 0 1-1 0v-.5a.5.5 0 0 1 .5-.5M5 10v.5a.5.5 0 0 1-1 0V10a.5.5 0 0 1 1 0m3 .5A2.5 2.5 0 0 1 10.5 8h5a2.5 2.5 0 0 1 2.5 2.5v5c0 .51-.152.983-.414 1.379l-3.377-3.377a1.71 1.71 0 0 0-2.418 0L8.414 16.88A2.5 2.5 0 0 1 8 15.5zm6 .5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-4.88 6.586c.396.262.87.414 1.379.414h5c.51 0 .983-.152 1.379-.414l-3.377-3.377a.71.71 0 0 0-1.004 0z");
}

</style>
