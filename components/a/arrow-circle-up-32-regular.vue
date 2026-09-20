<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ojmqxdh0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-32-regular" /></template>
<style>
.ojmqxdh0w {
  fill: currentColor;
  d: path("M9.293 16.707a1 1 0 0 0 1.414 0L15 12.414V22a1 1 0 1 0 2 0v-9.586l4.293 4.293a1 1 0 0 0 1.414-1.414l-6-6a1 1 0 0 0-1.414 0l-6 6a1 1 0 0 0 0 1.414M2 16c0 7.732 6.268 14 14 14s14-6.268 14-14S23.732 2 16 2S2 8.268 2 16m14 12C9.373 28 4 22.627 4 16S9.373 4 16 4s12 5.373 12 12s-5.373 12-12 12");
}

</style>
