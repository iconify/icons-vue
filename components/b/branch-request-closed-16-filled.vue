<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w9q2oy77p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-request-closed-16-filled" /></template>
<style>
.w9q2oy77p {
  fill: currentColor;
  d: path("M6 3.5a2.5 2.5 0 0 1-2 2.45v4.1a2.5 2.5 0 1 1-1 0v-4.1A2.5 2.5 0 1 1 6 3.5M12.5 15a2.5 2.5 0 0 0 .5-4.95V6.5a.5.5 0 0 0-1 0v3.55a2.5 2.5 0 0 0 .5 4.95M10.646 1.646a.5.5 0 0 1 .708 0L12.5 2.793l1.146-1.147a.5.5 0 0 1 .708.708L13.207 3.5l1.147 1.146a.5.5 0 0 1-.708.708L12.5 4.207l-1.146 1.147a.5.5 0 0 1-.708-.708L11.793 3.5l-1.147-1.146a.5.5 0 0 1 0-.708");
}

</style>
