<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="d6n96l47o"/><path class="ssx0gtxus"/><path class="tsg_iaz9j"/><path class="gguaoqbiu"/><path class="kdgr_ibkc"/><path class="xrfxk7sxz"/><path class="liikt8bde"/><g class="rqrkiubik"><circle class="vetj0jikt"/><circle class="ngds8nbum"/><circle class="azkctnbyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ballot-box-with-ballot" /></template>
<style>
.azkctnbyv {
  cx: 13px;
  cy: 13px;
  r: 1px;
}

.d6n96l47o {
  fill: var(--svg-color--8ccaf7, #8ccaf7);
  d: path("M34.5 24.995c0 2.209-1.791 2-4 2h-25c-2.209 0-4 .209-4-2L3.5 11c.293-1.75 1-2 2-2h25c1 0 1.791.208 2 2z");
}

.gguaoqbiu {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M34.5 25a2 2 0 0 0-2-2h-29a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h29a2 2 0 0 0 2-2z");
}

.kdgr_ibkc {
  fill: var(--svg-color--4289c1, #4289c1);
  d: path("M13.5 23v6a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2v-6z");
}

.liikt8bde {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M24 5a.5.5 0 0 1-.5.5H16a.5.5 0 0 1 0-1h7.5a.5.5 0 0 1 .5.5m0 4a.5.5 0 0 1-.5.5H16a.5.5 0 0 1 0-1h7.5a.5.5 0 0 1 .5.5m0 4a.5.5 0 0 1-.5.5H16a.5.5 0 0 1 0-1h7.5a.5.5 0 0 1 .5.5");
}

.ngds8nbum {
  cx: 13px;
  cy: 9px;
  r: 1px;
}

.rqrkiubik {
  fill: var(--svg-color--c1694f, #c1694f);
}

.ssx0gtxus {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M28.5 16.5A1.5 1.5 0 0 1 27 18H9a1.5 1.5 0 1 1 0-3h18a1.5 1.5 0 0 1 1.5 1.5");
}

.tsg_iaz9j {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M26.25 17.188v-14a2 2 0 0 0-2-2h-13a2 2 0 0 0-2 2v14z");
}

.vetj0jikt {
  cx: 13px;
  cy: 5px;
  r: 1px;
}

.xrfxk7sxz {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M22.5 23v-1a2 2 0 0 0-2-2h-5a2 2 0 0 0-2 2v1zm-3 4.5a1.5 1.5 0 0 1-3 0v-1a1.5 1.5 0 1 1 3 0z");
}

</style>
