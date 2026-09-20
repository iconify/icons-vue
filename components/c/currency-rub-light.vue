<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cbvvuibrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-rub-light" /></template>
<style>
.cbvvuibrn {
  fill: currentColor;
  d: path("M148 150a58 58 0 0 0 0-116H88a6 6 0 0 0-6 6v98H56a6 6 0 0 0 0 12h26v20H56a6 6 0 0 0 0 12h26v34a6 6 0 0 0 12 0v-34h50a6 6 0 0 0 0-12H94v-20ZM94 46h54a46 46 0 0 1 0 92H94Z");
}

</style>
