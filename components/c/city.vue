<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ly_q9m19z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:city" /></template>
<style>
.ly_q9m19z {
  fill: currentColor;
  d: path("M240 208h-8V88a8 8 0 0 0-8-8h-64a8 8 0 0 0-8 8v40h-48V40a8 8 0 0 0-8-8H32a8 8 0 0 0-8 8v168h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16M168 96h48v112h-48Zm-16 48v64h-48v-64ZM40 48h48v160H40Zm32 24v16a8 8 0 0 1-16 0V72a8 8 0 0 1 16 0m0 48v16a8 8 0 0 1-16 0v-16a8 8 0 0 1 16 0m0 48v16a8 8 0 0 1-16 0v-16a8 8 0 0 1 16 0m48 16v-16a8 8 0 0 1 16 0v16a8 8 0 0 1-16 0m64 0v-16a8 8 0 0 1 16 0v16a8 8 0 0 1-16 0m0-48v-16a8 8 0 0 1 16 0v16a8 8 0 0 1-16 0");
}

</style>
