<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG6DNCsdvf"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="tm0qpkhga"/></mask></defs><circle mask="url(#SVG6DNCsdvf)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:folder-circle-filled" /></template>
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

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.tm0qpkhga {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M18.5 8h-4.991l-.565-.988A3 3 0 0 0 10.34 5.5H7.5a3 3 0 0 0-3 3V18a3 3 0 0 0 3 3h11a3 3 0 0 0 3-3v-7a3 3 0 0 0-3-3m-11 11a1 1 0 0 1-1-1V8.5a1 1 0 0 1 1-1h2.84a1 1 0 0 1 .868.504l.852 1.492a1 1 0 0 0 .869.504H18.5a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1z");
}

</style>
