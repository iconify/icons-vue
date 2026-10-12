<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qrtz7gkqp"/><path class="b1h5cyb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:income-statement-sharp" /></template>
<style>
.b1h5cyb2e {
  d: path("m8 17.25l2.5-2.5l2 2l3.5-3.5");
}

.qrtz7gkqp {
  d: path("M4.25 2.75h15.5v18.5H4.25zM8 7h8m-8 3.25h5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
