<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="nryxmsbtn"/><path class="ed_vk1bec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blinds-sharp-fill" /></template>
<style>
.ed_vk1bec {
  d: path("M12 14L12 18");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nryxmsbtn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 3.0001L21 14C21 14.5523 20.5523 15 20 15L4 15C3.4477 15 3 14.5523 3 14L3 3.0001L1 3.0001L1 1.0001L3.988 1.0001C3.992 1 3.996 1 4 1L20 1C20.004 1 20.008 1 20.012 1.0001L23 1.0001L23 3.0001L21 3.0001ZM7 5L7 7L17 7L17 5L7 5ZM7 9L7 11L17 11L17 9L7 9ZM15 20C15 21.6569 13.6569 23 12 23C10.3431 23 9 21.6569 9 20C9 18.3431 10.3431 17 12 17C13.6569 17 15 18.3431 15 20Z");
  stroke: none;
}

</style>
