<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGZGSE3jWA"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="jm-x3mhqb"/><path class="lzean3b2l"/></g></mask></defs><circle mask="url(#SVGZGSE3jWA)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:exclamation-circle-filled" /></template>
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

.jm-x3mhqb {
  fill-rule: evenodd;
  d: path("M13 5a2 2 0 0 1 2 2v7a2 2 0 1 1-4 0V7a2 2 0 0 1 2-2");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.lzean3b2l {
  d: path("M15 19a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
