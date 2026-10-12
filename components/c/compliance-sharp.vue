<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="opc3-u8fn"/><path class="zewuj8bmh"/><circle class="o2mgrpbno"/><path class="sjcx_2czi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compliance-sharp" /></template>
<style>
.o2mgrpbno {
  cx: 16.5px;
  cy: 15.25px;
  r: 3.25px;
}

.opc3-u8fn {
  d: path("M11.5 21.25H4.75V2.75h9l5.5 5.5v2");
}

.sjcx_2czi {
  d: path("M14.75 18v3.25L16.5 20l1.75 1.25V18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zewuj8bmh {
  d: path("M13.75 2.75v5.5h5.5m-11 3.5h3.5M8.25 15h2");
}

</style>
