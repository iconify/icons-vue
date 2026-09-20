<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgg1stbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-selector-tool-rounded" /></template>
<style>
.bgg1stbrz {
  fill: currentColor;
  d: path("M15.15 21.375q-.575.275-1.15.063t-.85-.788l-3-6.45l-2.325 3.25q-.425.6-1.125.375t-.7-.95V4.05q0-.625.563-.9t1.062.125l10.1 7.95q.575.425.338 1.1T17.1 13h-4.2l2.975 6.375q.275.575.063 1.15t-.788.85");
}

</style>
