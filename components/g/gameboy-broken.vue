<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xs3pxobcu"/><path class="kssj5tb7x"/><path class="rn5innbyw"/><path class="ixis8j2zi"/><path class="hkzwun7yv"/><path class="b8_i36bih"/><path class="lkjawhb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gameboy-broken" /></template>
<style>
.b8_i36bih {
  stroke-linejoin: round;
  d: path("M15.5 17.166H15.5001");
}

.hkzwun7yv {
  stroke-linejoin: round;
  d: path("M17.1665 15.5H17.1666");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixis8j2zi {
  stroke-linejoin: round;
  d: path("M13.8335 15.5H13.8336");
}

.kssj5tb7x {
  d: path("M8.11177 9.94889C7.59413 9.81019 7.18981 9.40587 7.05111 8.88823C7 8.69748 7 8.46499 7 8C7 7.53501 7 7.30252 7.05111 7.11177C7.18981 6.59413 7.59413 6.18981 8.11177 6.05111C8.30252 6 8.53501 6 9 6H15C15.465 6 15.6975 6 15.8882 6.05111C16.4059 6.18981 16.8102 6.59413 16.9489 7.11177C17 7.30252 17 7.53501 17 8C17 8.46499 17 8.69748 16.9489 8.88823C16.8102 9.40587 16.4059 9.81019 15.8882 9.94889C15.6975 10 15.465 10 15 10H12");
}

.lkjawhb3k {
  stroke-linejoin: round;
  d: path("M15.4995 13.833H15.4996");
}

.rn5innbyw {
  stroke-linejoin: round;
  d: path("M8.5 14V15.5M8.5 15.5V17M8.5 15.5H7M8.5 15.5L10 15.5");
}

.xs3pxobcu {
  d: path("M21 12C21 16.714 21 19.0711 19.682 20.5355C18.364 22 16.2426 22 12 22C7.75736 22 5.63604 22 4.31802 20.5355C3 19.0711 3 16.714 3 12C3 7.28595 3 4.92893 4.31802 3.46447C5.63604 2 7.75736 2 12 2C16.2426 2 18.364 2 19.682 3.46447C20.5583 4.43821 20.852 5.80655 20.9504 8");
}

</style>
