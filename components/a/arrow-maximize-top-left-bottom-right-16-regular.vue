<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bsnj6yb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-top-left-bottom-right-16-regular" /></template>
<style>
.bsnj6yb-d {
  fill: currentColor;
  d: path("M8.5 3a.5.5 0 0 1 0 1H4.707L12 11.293V7.5a.5.5 0 0 1 1 0v4.9a.6.6 0 0 1-.6.6H7.5a.5.5 0 0 1 0-1h3.793L4 4.707V8.5a.5.5 0 0 1-1 0V3.6a.6.6 0 0 1 .6-.6z");
}

</style>
