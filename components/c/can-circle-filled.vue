<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG5mGD2dNb"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="kcflzabqt"/><path class="g71iogflb"/></g></mask></defs><circle mask="url(#SVG5mGD2dNb)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:can-circle-filled" /></template>
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

.g71iogflb {
  d: path("M10 12.5a4 4 0 1 0 8 0a4 4 0 0 0-8 0m2.805 1.406q-.37.09-1.221.372l-.061-.085c1.258-.378 2.272-.955 3.032-1.734q1.025-1.047 1.382-2.25q.224.19.407.419c.124.835.03 1.457-.259 1.884c-.355.526-.95.855-1.505 1c-.071.019-.2.048-.402.092l-.398.085l-.213.045l-.113.024c-.274.06-.483.107-.65.148");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kcflzabqt {
  d: path("M15.5 5h-5Q8 6 7.5 8v10a3 3 0 0 0 3 3h5a3 3 0 0 0 3-3V8q-.5-2-3-3m-6 13V8.294c.19-.502.624-.926 1.411-1.294h4.178c.787.368 1.221.792 1.411 1.294V18a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

</style>
