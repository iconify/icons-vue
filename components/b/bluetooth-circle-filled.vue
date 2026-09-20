<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGCgEoGedn"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="h3py7f4sn"/><path clip-rule="evenodd" class="zo1k_nbcm"/><path class="c9fz2s_sr"/><path class="alfhacw0e"/></g></mask></defs><circle mask="url(#SVGCgEoGedn)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bluetooth-circle-filled" /></template>
<style>
.alfhacw0e {
  d: path("M14.526 13.802a1 1 0 1 0-1.195-1.604l-6.965 5.195a1 1 0 0 0 1.196 1.603z");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.c9fz2s_sr {
  d: path("M14.526 12.198a1 1 0 1 1-1.195 1.604L6.366 8.607a1 1 0 1 1 1.196-1.603z");
}

.ft5dv1b6b {
  fill: none;
}

.h3py7f4sn {
  fill-rule: evenodd;
  d: path("m14.535 13.795l5.572-4.25a1 1 0 0 0 0-1.59l-5.572-4.25a1 1 0 0 0-1.606.795V13a1 1 0 0 0 1.606.795m.394-7.274L17.85 8.75l-2.922 2.23z");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.zo1k_nbcm {
  fill-rule: evenodd;
  d: path("m14.535 22.295l5.572-4.25a1 1 0 0 0 0-1.59l-5.572-4.25A1 1 0 0 0 12.93 13v8.5a1 1 0 0 0 1.606.795m.394-7.274l2.922 2.229l-2.922 2.23z");
}

</style>
