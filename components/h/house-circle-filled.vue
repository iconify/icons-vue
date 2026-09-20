<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGxcCLibXR"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="ilse98yis"/></mask></defs><circle mask="url(#SVGxcCLibXR)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:house-circle-filled" /></template>
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

.ilse98yis {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M4 14c-.92 0-1.352-1.137-.664-1.747l9-8a1 1 0 0 1 1.328 0l9 8c.688.61.255 1.747-.664 1.747h-1v7a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-7zm6 6v-5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v5h3v-7a1 1 0 0 1 .512-.873L13 6.337l-6.512 5.79A1 1 0 0 1 7 13v7zm2 0v-4h2v4z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
