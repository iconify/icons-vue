<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mbzkw9b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:file-magnifying-glass-light" /></template>
<style>
.mbzkw9b7t {
  fill: currentColor;
  d: path("m212.24 83.76l-56-56A6 6 0 0 0 152 26H56a14 14 0 0 0-14 14v176a14 14 0 0 0 14 14h144a14 14 0 0 0 14-14V88a6 6 0 0 0-1.76-4.24M158 46.48L193.52 82H158ZM200 218H56a2 2 0 0 1-2-2V40a2 2 0 0 1 2-2h90v50a6 6 0 0 0 6 6h50v122a2 2 0 0 1-2 2m-48.11-50.59a34.05 34.05 0 1 0-8.48 8.48l12.35 12.35a6 6 0 0 0 8.48-8.48ZM102 148a22 22 0 1 1 22 22a22 22 0 0 1-22-22");
}

</style>
