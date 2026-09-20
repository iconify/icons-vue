<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zy1ovrbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:avocado" /></template>
<style>
.zy1ovrbix {
  fill: currentColor;
  d: path("M128 112a48 48 0 1 0 48 48a48.05 48.05 0 0 0-48-48m0 80a32 32 0 1 1 32-32a32 32 0 0 1-32 32m83-61.34l-29.8-84.19a56 56 0 0 0-106-1.14l-29.51 83.5A88 88 0 1 0 211 130.66M128 232a72.05 72.05 0 0 1-67.33-97.57a1.3 1.3 0 0 1 .07-.18l29.54-83.59a40 40 0 0 1 75.74.88l.06.18L195.9 136a72.05 72.05 0 0 1-67.9 96");
}

</style>
