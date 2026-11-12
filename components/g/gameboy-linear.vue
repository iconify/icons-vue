<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aymhwhb8v"/><path class="er5hmdbdf"/><path class="rn5innbyw"/><path class="klcdbfe3f"/><path class="cz3jkzutv"/><path class="zhbw671gb"/><path class="lkjawhb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gameboy-linear" /></template>
<style>
.aymhwhb8v {
  d: path("M12 22C7.75736 22 5.63604 22 4.31802 20.5355C3 19.0711 3 16.714 3 12C3 7.28595 3 4.92893 4.31802 3.46447C5.63604 2 7.75736 2 12 2C16.2426 2 18.364 2 19.682 3.46447C21 4.92893 21 7.28595 21 12C21 16.714 21 19.0711 19.682 20.5355C18.364 22 16.2426 22 12 22Z");
}

.cz3jkzutv {
  stroke-linejoin: round;
  d: path("M17.1667 15.5004H17.1668");
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

.klcdbfe3f {
  stroke-linejoin: round;
  d: path("M13.8333 15.5004H13.8334");
}

.lkjawhb3k {
  stroke-linejoin: round;
  d: path("M15.4995 13.833H15.4996");
}

.rn5innbyw {
  stroke-linejoin: round;
  d: path("M8.5 14V15.5M8.5 15.5V17M8.5 15.5H7M8.5 15.5L10 15.5");
}

.zhbw671gb {
  stroke-linejoin: round;
  d: path("M15.4998 17.1664H15.4999");
}

</style>
