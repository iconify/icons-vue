<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aymhwhb8v"/><path class="er5hmdbdf"/><path class="deivui2dq"/><path class="xhkm7y-hu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calculator-linear" /></template>
<style>
.aymhwhb8v {
  d: path("M12 22C7.75736 22 5.63604 22 4.31802 20.5355C3 19.0711 3 16.714 3 12C3 7.28595 3 4.92893 4.31802 3.46447C5.63604 2 7.75736 2 12 2C16.2426 2 18.364 2 19.682 3.46447C21 4.92893 21 7.28595 21 12C21 16.714 21 19.0711 19.682 20.5355C18.364 22 16.2426 22 12 22Z");
}

.deivui2dq {
  stroke-linejoin: round;
  d: path("M8 13H8.009M11.991 13H12M15.991 13H16");
}

.er5hmdbdf {
  d: path("M9 10H15C15.465 10 15.6975 10 15.8882 9.94889C16.4059 9.81019 16.8102 9.40587 16.9489 8.88823C17 8.69748 17 8.46499 17 8C17 7.53501 17 7.30252 16.9489 7.11177C16.8102 6.59413 16.4059 6.18981 15.8882 6.05111C15.6975 6 15.465 6 15 6H9C8.53501 6 8.30252 6 8.11177 6.05111C7.59413 6.18981 7.18981 6.59413 7.05111 7.11177C7 7.30252 7 7.53501 7 8C7 8.46499 7 8.69748 7.05111 8.88823C7.18981 9.40587 7.59413 9.81019 8.11177 9.94889C8.30252 10 8.53501 10 9 10Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhkm7y-hu {
  stroke-linejoin: round;
  d: path("M8 17H8.009M11.991 17H12M15.991 17H16");
}

</style>
