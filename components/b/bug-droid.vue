<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="izrqq-9xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bug-droid" /></template>
<style>
.izrqq-9xh {
  fill: currentColor;
  d: path("m191.83 51.48l13.83-13.82a8 8 0 0 0-11.32-11.32L179.79 40.9a87.81 87.81 0 0 0-103.58 0L61.66 26.34a8 8 0 0 0-11.32 11.32l13.83 13.82A87.72 87.72 0 0 0 40 112v40a88 88 0 0 0 176 0v-40a87.72 87.72 0 0 0-24.17-60.52M128 40a72.08 72.08 0 0 1 72 72v8H56v-8a72.08 72.08 0 0 1 72-72m0 184a72.08 72.08 0 0 1-72-72v-16h144v16a72.08 72.08 0 0 1-72 72m16-132a12 12 0 1 1 12 12a12 12 0 0 1-12-12m-56 0a12 12 0 1 1 12 12a12 12 0 0 1-12-12");
}

</style>
