<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fkhwshbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-split-20-filled" /></template>
<style>
.fkhwshbzu {
  fill: currentColor;
  d: path("M18 10a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-9.207 2.414a.5.5 0 1 0-.707-.707l-.586.586V9h5v3.293l-.586-.586a.5.5 0 0 0-.707.707l1.44 1.44a.5.5 0 0 0 .707 0l1.439-1.44a.5.5 0 0 0-.707-.707l-.586.586V8.5A.5.5 0 0 0 13 8h-2.5V5.5a.5.5 0 0 0-1 0V8H7a.5.5 0 0 0-.5.5v3.793l-.586-.586a.5.5 0 0 0-.707.707l1.44 1.44a.5.5 0 0 0 .707 0z");
}

</style>
