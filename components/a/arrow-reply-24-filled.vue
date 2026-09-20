<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuf3n_b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-24-filled" /></template>
<style>
.nuf3n_b1y {
  fill: currentColor;
  d: path("M9.707 6.707a1 1 0 0 0-1.414-1.414l-5 5a1 1 0 0 0 0 1.414l5 5a1 1 0 0 0 1.414-1.414L6.414 12H13a6 6 0 0 1 6 6a1 1 0 1 0 2 0a8 8 0 0 0-8-8H6.414z");
}

</style>
