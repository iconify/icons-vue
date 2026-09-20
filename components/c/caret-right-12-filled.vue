<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m93ast6nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-right-12-filled" /></template>
<style>
.m93ast6nk {
  fill: currentColor;
  d: path("M5.702 3.282C5.069 2.659 4 3.107 4 3.994v4.012c0 .887 1.07 1.335 1.702.713l2.037-2.006a1 1 0 0 0 0-1.425z");
}

</style>
