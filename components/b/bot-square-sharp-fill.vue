<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fks0f3imz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-square-sharp-fill" /></template>
<style>
.fks0f3imz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM10.882 6.9042L11.593 11.5685L13.5701 11.2671L12.8591 6.6028ZM14.8363 6.3014L15.5473 10.9657L17.5244 10.6643L16.8134 6Z");
}

</style>
