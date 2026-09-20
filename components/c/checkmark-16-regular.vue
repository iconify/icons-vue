<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ps9ac6d2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-16-regular" /></template>
<style>
.ps9ac6d2x {
  fill: currentColor;
  d: path("M13.864 3.655a.5.5 0 0 1-.021.707l-7.93 7.474a.6.6 0 0 1-.839-.016L2.394 9.1a.5.5 0 0 1 .712-.702l2.406 2.442l7.645-7.206a.5.5 0 0 1 .707.021");
}

</style>
