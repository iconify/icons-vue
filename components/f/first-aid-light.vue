<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h47d66b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:first-aid-light" /></template>
<style>
.h47d66b0y {
  fill: currentColor;
  d: path("M216 90h-50V40a14 14 0 0 0-14-14h-48a14 14 0 0 0-14 14v50H40a14 14 0 0 0-14 14v48a14 14 0 0 0 14 14h50v50a14 14 0 0 0 14 14h48a14 14 0 0 0 14-14v-50h50a14 14 0 0 0 14-14v-48a14 14 0 0 0-14-14m2 62a2 2 0 0 1-2 2h-56a6 6 0 0 0-6 6v56a2 2 0 0 1-2 2h-48a2 2 0 0 1-2-2v-56a6 6 0 0 0-6-6H40a2 2 0 0 1-2-2v-48a2 2 0 0 1 2-2h56a6 6 0 0 0 6-6V40a2 2 0 0 1 2-2h48a2 2 0 0 1 2 2v56a6 6 0 0 0 6 6h56a2 2 0 0 1 2 2Z");
}

</style>
