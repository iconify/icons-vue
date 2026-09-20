<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhnwmiftk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-multiple-concentric-16-filled" /></template>
<style>
.qhnwmiftk {
  fill: currentColor;
  d: path("M2.5 8a5.5 5.5 0 1 1 11 0a5.5 5.5 0 0 1-11 0M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1M5.5 8a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0M8 4a4 4 0 1 0 0 8a4 4 0 0 0 0-8");
}

</style>
