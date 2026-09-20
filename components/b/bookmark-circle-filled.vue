<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGKs5vXIss"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="hx57ubbfk"/></mask></defs><circle mask="url(#SVGKs5vXIss)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bookmark-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.hx57ubbfk {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m9.245 20.667l3.755-4.2l3.755 4.2c.612.684 1.745.251 1.745-.667V6a1 1 0 0 0-1-1h-9a1 1 0 0 0-1 1v14c0 .918 1.134 1.35 1.745.666M9.5 17.38V7h7v10.381l-2.754-3.08a1 1 0 0 0-1.491 0z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
