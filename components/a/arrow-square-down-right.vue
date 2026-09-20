<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="okju-pjda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-square-down-right" /></template>
<style>
.okju-pjda {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m0 176H48V48h160ZM90.34 101.66a8 8 0 0 1 11.32-11.32L152 140.69V112a8 8 0 0 1 16 0v48a8 8 0 0 1-8 8h-48a8 8 0 0 1 0-16h28.69Z");
}

</style>
