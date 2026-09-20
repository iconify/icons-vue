<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG8YYpzdUK"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="k_km87bsb"/><path class="hfm5n6g2m"/></g></mask></defs><circle mask="url(#SVG8YYpzdUK)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:flower-bud-circle-filled" /></template>
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

.hfm5n6g2m {
  d: path("M16.5 13a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k_km87bsb {
  fill-rule: evenodd;
  d: path("M19.49 16.714a4.003 4.003 0 0 0 0-7.427q.01-.143.01-.287A4 4 0 0 0 13 5.877a4 4 0 0 0-6.49 3.41a4.003 4.003 0 0 0 0 7.427q-.01.142-.01.286a4 4 0 0 0 6.5 3.123a4 4 0 0 0 6.49-3.41m-2.108-7.036a1 1 0 0 0 .835 1.334a2 2 0 0 1 0 3.976a1 1 0 0 0-.835 1.334q.117.324.118.678a2 2 0 0 1-3.667 1.105a1 1 0 0 0-1.666 0a2 2 0 0 1-3.55-1.783a1 1 0 0 0-.834-1.333a2 2 0 0 1 0-3.977a1 1 0 0 0 .835-1.334a2 2 0 0 1 3.55-1.783a1 1 0 0 0 1.665 0a2 2 0 0 1 3.55 1.783");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
