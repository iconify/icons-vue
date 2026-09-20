<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ittqilbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-12-regular" /></template>
<style>
.ittqilbmb {
  fill: currentColor;
  d: path("M6 0a2.5 2.5 0 0 1 2.5 2.5v1.565A2 2 0 0 1 10 6v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 1.5-1.935V2.5A2.5 2.5 0 0 1 6 0M4 5a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1zm2 1.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5M6 1a1.5 1.5 0 0 0-1.5 1.5V4h3V2.5A1.5 1.5 0 0 0 6 1");
}

</style>
