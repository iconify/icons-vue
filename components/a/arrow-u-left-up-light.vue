<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ebzzlv-1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-left-up-light" /></template>
<style>
.ebzzlv-1y {
  fill: currentColor;
  d: path("M206 80v88a62 62 0 0 1-124 0V46.49L44.24 84.24a6 6 0 0 1-8.48-8.48l48-48a6 6 0 0 1 8.48 0l48 48a6 6 0 1 1-8.48 8.48L94 46.49V168a50 50 0 0 0 100 0V80a6 6 0 0 1 12 0");
}

</style>
