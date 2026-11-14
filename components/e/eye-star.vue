<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tuwxt_bds"/><path class="cz_yibbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-star" /></template>
<style>
.cz_yibbtk {
  d: path("M7.25 9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.tuwxt_bds {
  d: path("M8.971 14.958c-2.799-.302-5.097-2.23-6.471-5.208C4 6.5 6.6 4.5 9.75 4.5c3.053 0 5.589 1.879 7.108 4.953m-1.155 2.456a8.6 8.6 0 0 1-1.892 1.815");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
