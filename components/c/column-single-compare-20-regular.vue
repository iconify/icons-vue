<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h6nai9bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-single-compare-20-regular" /></template>
<style>
.h6nai9bue {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v2h10V4a1 1 0 0 0-1-1zm-1 8h10V7H5zm0 3v2a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-2z");
}

</style>
