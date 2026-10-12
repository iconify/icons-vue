<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="aeb5g-brm"/><path class="z5-h2yp6f"/><circle class="io--5q1sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bond-certificate-sharp" /></template>
<style>
.aeb5g-brm {
  d: path("M2.75 3.25h18.5V18H2.75zm3.5 4h11.5m-11.5 3.5H10");
}

.io--5q1sp {
  cx: 15.5px;
  cy: 12.75px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5-h2yp6f {
  d: path("M14 15.05v6.2l1.5-1l1.5 1v-6.2");
}

</style>
