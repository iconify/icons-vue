<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="perppybwq"/><path class="a2-o0ifih"/><path class="v_n1r0bhx"/><path class="ehgiv7t3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-pump-station" /></template>
<style>
.a2-o0ifih {
  d: path("M5.5 10v11.5h4V10m0 3c3 0 3.5-3.5 6-3.5c1.5 0 1.5 1.5 1.5 4");
}

.ehgiv7t3r {
  d: path("M15.5 17.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.perppybwq {
  d: path("M3.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_n1r0bhx {
  d: path("M13 17.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-5.5-11l1.25-1.25");
}

</style>
