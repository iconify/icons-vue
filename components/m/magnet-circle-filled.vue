<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGxW22CbWl"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="h2-x_cbyv"/><path class="ef70tmazi"/></g></mask></defs><circle mask="url(#SVGxW22CbWl)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:magnet-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ef70tmazi {
  d: path("m10.293 11.464l-2.121-2.12l1.414-1.415l2.121 2.121zm6.364 6.364l-2.121-2.12l1.414-1.415l2.121 2.121zm.972-8.4a1 1 0 0 1-.558-1.3l1.35-3.375l1.559.52l.819-1.706a1 1 0 0 1 1.803.866L21.02 7.727l-1.442-.48l-.65 1.624a1 1 0 0 1-1.3.557");
}

.ft5dv1b6b {
  fill: none;
}

.h2-x_cbyv {
  d: path("M10.293 4.393a1 1 0 0 1 1.414 0l3.536 3.536a1 1 0 0 1 0 1.414l-4.95 4.95a1 1 0 1 0 1.414 1.414l4.95-4.95a1 1 0 0 1 1.414 0l3.536 3.536a1 1 0 0 1 0 1.414l-4.95 4.95A8 8 0 1 1 5.343 9.343zM11 6.515l-4.243 4.242a6 6 0 1 0 8.486 8.486L19.485 15l-2.121-2.121l-4.243 4.242A3 3 0 1 1 8.88 12.88l4.242-4.243z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

</style>
