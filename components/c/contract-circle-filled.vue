<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGUERWfbkM"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="a3xxuxmnr"/><path class="czql5vb5f"/><path class="uugwspwfq"/><path class="d60od6b4m"/><path class="qqz61wshz"/></g></mask></defs><circle mask="url(#SVGUERWfbkM)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:contract-circle-filled" /></template>
<style>
.a3xxuxmnr {
  d: path("M14.707 12.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.czql5vb5f {
  d: path("M14 13a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.d60od6b4m {
  d: path("M13 18a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0z");
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

.qqz61wshz {
  d: path("M8 15a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.uugwspwfq {
  d: path("M15 12a1 1 0 1 1-2 0V8a1 1 0 1 1 2 0zm-6.293 6.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

</style>
