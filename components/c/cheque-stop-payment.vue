<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w2gk0lagt"/><path class="cpc6ltm1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-stop-payment" /></template>
<style>
.cpc6ltm1w {
  d: path("m19.339 14.766l1.895 1.895v2.678l-1.895 1.895h-2.678l-1.895-1.895v-2.678l1.895-1.895ZM16.75 18h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w2gk0lagt {
  d: path("M12 18.5H2.5v-13h19V13M6 9.5h5.5m-5.5 5h3.5");
}

</style>
