<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG35BUAcUy"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="zyhc4ob-x"/><path clip-rule="evenodd" class="z9nqsdprz"/><path class="vi-yg5enu"/><path class="txlqvcbnr"/></g></mask></defs><circle mask="url(#SVG35BUAcUy)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:controller-circle-filled" /></template>
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

.txlqvcbnr {
  d: path("M10 15a1 1 0 1 1-2 0v-4a1 1 0 0 1 2 0z");
}

.vi-yg5enu {
  d: path("M7 14a1 1 0 1 1 0-2h4a1 1 0 0 1 0 2z");
}

.z9nqsdprz {
  fill-rule: evenodd;
  d: path("M17.5 7h-9a5 5 0 0 0-5 5v2a5 5 0 0 0 5 5h9a5 5 0 0 0 5-5v-2a5 5 0 0 0-5-5m-12 5a3 3 0 0 1 3-3h9a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3z");
}

.zyhc4ob-x {
  d: path("M15.25 13a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m2 2.5a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5");
}

</style>
