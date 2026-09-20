<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rp4yjibkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lectern-thin" /></template>
<style>
.rp4yjibkn {
  fill: currentColor;
  d: path("m242.72 122.63l-40-80A11.93 11.93 0 0 0 192 36H64a11.93 11.93 0 0 0-10.73 6.63l-40 80A12 12 0 0 0 24 140h100v72H96a4 4 0 0 0 0 8h64a4 4 0 0 0 0-8h-28v-72h100a12 12 0 0 0 10.73-17.37Zm-7.33 7.47A3.94 3.94 0 0 1 232 132H24a4 4 0 0 1-3.58-5.79l40-80A4 4 0 0 1 64 44h128a4 4 0 0 1 3.58 2.21l40 80a3.94 3.94 0 0 1-.19 3.89M188 104a4 4 0 0 1-4 4H72a4 4 0 0 1 0-8h112a4 4 0 0 1 4 4");
}

</style>
