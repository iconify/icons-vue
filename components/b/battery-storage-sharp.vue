<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oo_-wxpvs"/><path class="tsqq5x2ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battery-storage-sharp" /></template>
<style>
.oo_-wxpvs {
  d: path("M2.75 6.25h18.5v15H2.75zm3 0v-2.5M12 6.25v-2.5m6.25 2.5v-2.5m-9.33 2.5v15m6.16-15v15");
}

.tsqq5x2ue {
  d: path("M12.75 10.5L11 13.75h2L11.25 17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
