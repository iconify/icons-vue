<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bxa-94bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-double-left-16-regular" /></template>
<style>
.bxa-94bji {
  fill: currentColor;
  d: path("M7.646 3.147a.5.5 0 0 1 .707.707L4.207 8l4.146 4.147a.499.499 0 1 1-.707.707l-4.5-4.5a.5.5 0 0 1 0-.707zm4 0a.5.5 0 0 1 .707.707L8.207 8l4.146 4.147a.5.5 0 0 1-.707.707l-4.5-4.5a.5.5 0 0 1 0-.707z");
}

</style>
