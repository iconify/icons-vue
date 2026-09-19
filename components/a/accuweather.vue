<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i1t9dnb_z"/><path class="d6i6qnr7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:accuweather" /></template>
<style>
.d6i6qnr7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.649 7.45l4.38-4.95l4.35 5.007l6.848-2.632v7.029l6.87.732l-1.634 6.998l5.037 4.33l-5.002 4.19l1.581 7.024l-6.852.884v6.88l-6.884-2.567l-4.304 5.125l-4.446-5.128l-6.763 2.579v-6.883l-6.934-.902L7.56 28.16L2.5 23.957l5.088-4.29l-1.616-7.006l6.847-.822V4.946z");
}

.i1t9dnb_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.045a12.954 12.954 0 0 0-9.16 22.114A12.954 12.954 0 1 0 33.16 14.84A13.1 13.1 0 0 0 24 11.045");
}

</style>
