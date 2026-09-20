<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dqehd_sro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clover-32-filled" /></template>
<style>
.dqehd_sro {
  fill: currentColor;
  d: path("M8.5 2a6.5 6.5 0 0 0 0 13H14a1 1 0 0 0 1-1V8.5A6.5 6.5 0 0 0 8.5 2m0 28a6.5 6.5 0 1 1 0-13H14a1 1 0 0 1 1 1v5.5A6.5 6.5 0 0 1 8.5 30m15-28a6.5 6.5 0 1 1 0 13H18a1 1 0 0 1-1-1V8.5A6.5 6.5 0 0 1 23.5 2m0 28a6.5 6.5 0 1 0 0-13H18a1 1 0 0 0-1 1v5.5a6.5 6.5 0 0 0 6.5 6.5");
}

</style>
