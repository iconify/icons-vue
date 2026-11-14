<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gnlnvqbyp"/><path class="x4h68jbhs"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-pending" /></template>
<style>
.gnlnvqbyp {
  d: path("M12.7 18.5H2.5v-13h19v6.4m0 5.9v.4M6 9.5h5.5m-5.5 5h3.5m6 .25h5m-5 6.5h5");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4h68jbhs {
  d: path("M16.5 14.75v1l3 4.5v1");
}

</style>
