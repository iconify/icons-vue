<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l2u6dtb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-left-down-thin" /></template>
<style>
.l2u6dtb5z {
  fill: currentColor;
  d: path("M204 32a4 4 0 0 1-4 4a92.1 92.1 0 0 0-92 92v86.34l41.17-41.17a4 4 0 0 1 5.66 5.66l-48 48a4 4 0 0 1-5.66 0l-48-48a4 4 0 0 1 5.66-5.66L100 214.34V128A100.11 100.11 0 0 1 200 28a4 4 0 0 1 4 4");
}

</style>
