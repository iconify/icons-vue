<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="egfo5db-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:desk-fill" /></template>
<style>
.egfo5db-q {
  fill: currentColor;
  d: path("M248 64H8a8 8 0 0 0 0 16h8v112a8 8 0 0 0 16 0v-48h192v48a8 8 0 0 0 16 0V80h8a8 8 0 0 0 0-16M80 112H56a8 8 0 0 1 0-16h24a8 8 0 0 1 0 16m56 8a8 8 0 0 1-16 0V88a8 8 0 0 1 16 0Zm64-8h-24a8 8 0 0 1 0-16h24a8 8 0 0 1 0 16");
}

</style>
