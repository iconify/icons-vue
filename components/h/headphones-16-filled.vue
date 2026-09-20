<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m6y4zz83b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-16-filled" /></template>
<style>
.m6y4zz83b {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7v4.5a2.5 2.5 0 0 1-2.5 2.5h-2a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 .5-.5H14V8A6 6 0 0 0 2 8v1h3.5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-2a2.5 2.5 0 0 1-2.487-2.244L1 12.5V8a7 7 0 0 1 7-7");
}

</style>
