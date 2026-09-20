<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m18qbehnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-up-24-filled" /></template>
<style>
.m18qbehnu {
  fill: currentColor;
  d: path("m7.293 8.293l3.995-4a1 1 0 0 1 1.32-.084l.094.083l4.006 4a1 1 0 0 1-1.32 1.499l-.094-.083l-2.293-2.291v11.584a1 1 0 0 1-.883.993L12 20a1 1 0 0 1-.993-.884L11 19.001V7.41L8.707 9.707a1 1 0 0 1-1.32.084l-.094-.084a1 1 0 0 1-.084-1.32zl3.995-4z");
}

</style>
