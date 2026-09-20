<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7txd-bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-up-right-32-light" /></template>
<style>
.c7txd-bof {
  fill: currentColor;
  d: path("M19.146 5.146a.5.5 0 0 0 0 .708L24.293 11H13a7 7 0 1 0 0 14h9.5a.5.5 0 0 0 0-1H13a6 6 0 0 1 0-12h11.293l-5.147 5.146a.5.5 0 0 0 .708.708l6-6a.5.5 0 0 0 0-.708l-6-6a.5.5 0 0 0-.708 0");
}

</style>
