<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ai6h05jkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-left-16-regular" /></template>
<style>
.ai6h05jkf {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-7a7 7 0 1 0 0 14A7 7 0 0 0 8 1M5.5 5a.5.5 0 0 0-.5.5V10a.5.5 0 0 0 1 0V6.707l3.646 3.647a.5.5 0 0 0 .708-.708L6.707 6H10a.5.5 0 0 0 0-1z");
}

</style>
