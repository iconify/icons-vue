<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG9bmlnepF"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="bk3_hoper"/><path class="unr03_lwc"/></g></mask></defs><circle mask="url(#SVG9bmlnepF)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cart-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bk3_hoper {
  fill-rule: evenodd;
  d: path("M19.513 9h-9.026a2.5 2.5 0 0 0-2.437 3.057l.913 4A2.5 2.5 0 0 0 11.401 18H18.6a2.5 2.5 0 0 0 2.437-1.943l.913-4A2.5 2.5 0 0 0 19.513 9m-9.137 2.013a.5.5 0 0 1 .111-.013h9.026a.5.5 0 0 1 .487.611l-.913 4A.5.5 0 0 1 18.6 16h-7.2a.5.5 0 0 1-.487-.389l-.913-4a.5.5 0 0 1 .376-.598");
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

.unr03_lwc {
  d: path("M6.49 5H5a1 1 0 0 1 0-2h2.29a1 1 0 0 1 .975.78l2.71 12a1 1 0 1 1-1.95.44zM13 20.25a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0m7 0a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0");
}

</style>
