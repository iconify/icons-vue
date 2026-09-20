<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGKeLQNbMx"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="wyjwh8bgc"/><path class="apr1q4kay"/><path class="vr28qub5u"/><path class="g5jjq-1sk"/></g></mask></defs><circle mask="url(#SVGKeLQNbMx)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:leave-circle-filled" /></template>
<style>
.apr1q4kay {
  d: path("M18.027 16.768a1 1 0 0 1-.129-1.408l2.084-2.5a1 1 0 1 1 1.536 1.28l-2.083 2.5a1 1 0 0 1-1.408.128");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.g5jjq-1sk {
  d: path("M16 5.5a1 1 0 0 1 1 1v4a1 1 0 1 1-2 0v-4a1 1 0 0 1 1-1m0 10a1 1 0 0 1 1 1v4a1 1 0 1 1-2 0v-4a1 1 0 0 1 1-1m-9-10a1 1 0 0 1 1 1v14a1 1 0 1 1-2 0v-14a1 1 0 0 1 1-1");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.vr28qub5u {
  d: path("M20.5 13.5a1 1 0 0 1-1 1H13a1 1 0 1 1 0-2h6.5a1 1 0 0 1 1 1M6 6.5a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1m0 14a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1");
}

.wyjwh8bgc {
  d: path("M18.027 10.232a1 1 0 0 1 1.408.128l2.083 2.5a1 1 0 0 1-1.536 1.28l-2.084-2.5a1 1 0 0 1 .128-1.408");
}

</style>
