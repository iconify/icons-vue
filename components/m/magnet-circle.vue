<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h2-x_cbyv"/><path class="ef70tmazi"/><path class="hdxpysbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:magnet-circle" /></template>
<style>
.ef70tmazi {
  d: path("m10.293 11.464l-2.121-2.12l1.414-1.415l2.121 2.121zm6.364 6.364l-2.121-2.12l1.414-1.415l2.121 2.121zm.972-8.4a1 1 0 0 1-.558-1.3l1.35-3.375l1.559.52l.819-1.706a1 1 0 0 1 1.803.866L21.02 7.727l-1.442-.48l-.65 1.624a1 1 0 0 1-1.3.557");
}

.h2-x_cbyv {
  d: path("M10.293 4.393a1 1 0 0 1 1.414 0l3.536 3.536a1 1 0 0 1 0 1.414l-4.95 4.95a1 1 0 1 0 1.414 1.414l4.95-4.95a1 1 0 0 1 1.414 0l3.536 3.536a1 1 0 0 1 0 1.414l-4.95 4.95A8 8 0 1 1 5.343 9.343zM11 6.515l-4.243 4.242a6 6 0 1 0 8.486 8.486L19.485 15l-2.121-2.121l-4.243 4.242A3 3 0 1 1 8.88 12.88l4.242-4.243z");
}

.hdxpysbbn {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

</style>
