<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hyzcm7ixf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-12-filled" /></template>
<style>
.hyzcm7ixf {
  fill: currentColor;
  d: path("M10.78 1.22a.75.75 0 0 1 0 1.06L3.56 9.5h3.69a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75v-5.5a.75.75 0 0 1 1.5 0v3.69l7.22-7.22a.75.75 0 0 1 1.06 0");
}

</style>
