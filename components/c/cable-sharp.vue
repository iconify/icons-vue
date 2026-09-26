<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd4nsybqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cable-sharp" /></template>
<style>
.zd4nsybqy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 4L6 4C3.7909 4 2 5.7909 2 8C2 10.2091 3.7909 12 6 12L18 12C20.2091 12 22 13.7909 22 16C22 18.2091 20.2091 20 18 20L10 20M14 2L20 2L20 6L14 6L14 2ZM4 18L10 18L10 22L4 22L4 18ZM20 4L23 4M4 20L1 20");
}

</style>
