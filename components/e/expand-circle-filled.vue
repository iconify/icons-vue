<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGwRDJbdfq"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="m_7ikbc3l"/><path class="slbs5hhpe"/><path class="svgjwnbcw"/><path class="ybbiicqde"/><path class="krq75fo3g"/></g></mask></defs><circle mask="url(#SVGwRDJbdfq)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:expand-circle-filled" /></template>
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

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.krq75fo3g {
  d: path("M14 9a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.m_7ikbc3l {
  d: path("M8.707 18.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.slbs5hhpe {
  d: path("M8 19a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.svgjwnbcw {
  d: path("M9 18a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0zm5.707-5.293a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.ybbiicqde {
  d: path("M19 12a1 1 0 1 1-2 0V8a1 1 0 1 1 2 0z");
}

</style>
