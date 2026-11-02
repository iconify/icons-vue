<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wznoccb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-fill" /></template>
<style>
.wznoccb4t {
  fill: currentColor;
  d: path("m4.707 1.293l14 14a.999.999 0 1 1-1.414 1.414L15 14.414V18a1 1 0 0 1-.553.894l-4 2A1 1 0 0 1 9 20v-7.586L3.293 6.707A1 1 0 0 1 3 6V5c0-.677.341-1.308.909-1.677l-.616-.616a.999.999 0 1 1 1.414-1.414M9.243 3H19a2 2 0 0 1 2 2v1c0 .265-.105.52-.293.707l-3.879 3.879Z");
}

</style>
