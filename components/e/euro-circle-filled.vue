<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGGNSfLdBN"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="xingkg3ey"/><path class="hb82rqb2h"/></g></mask></defs><circle mask="url(#SVGGNSfLdBN)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:euro-circle-filled" /></template>
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

.hb82rqb2h {
  d: path("M6 11a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1m0 3.5a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.xingkg3ey {
  d: path("M15.489 7C12.43 7 10 9.213 10 12.5c0 3.387 2.527 6 5.489 6c.743 0 1.451-.161 2.098-.454a1 1 0 1 1 .826 1.821a7.1 7.1 0 0 1-2.924.633C11.283 20.5 8 16.846 8 12.5C8 8.055 11.38 5 15.489 5q1.855.001 3.574 1.174a1 1 0 1 1-1.126 1.652C17.079 7.242 16.274 7 15.489 7");
}

</style>
