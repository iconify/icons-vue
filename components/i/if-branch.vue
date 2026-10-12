<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsr0blbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:if-branch" /></template>
<style>
.bsr0blbev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.88 3.63l3.49 3.49q.88.88 0 1.76l-3.49 3.49q-.88.88-1.76 0L7.63 8.88q-.88-.88 0-1.76l3.49-3.49q.88-.88 1.76 0M6.75 8H6.5a2 2 0 0 0-2 2v10.75M17.25 8h.25a2 2 0 0 1 2 2v10.75M2.75 19l1.75 1.75L6.25 19m11.5 0l1.75 1.75L21.25 19");
}

</style>
