<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="si_mtzbvj"/><path class="ok6un1e_l"/><path class="n0kyqub_b"/><path class="bh0wyoqvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cardholder-broken" /></template>
<style>
.bh0wyoqvw {
  d: path("M12 16H16M8 16H9");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0kyqub_b {
  d: path("M5 11H19");
}

.ok6un1e_l {
  d: path("M17 11V9.99999C17 8.11437 17 7.17156 16.4142 6.58577C15.9427 6.11423 15.2398 6.02227 14 6.00433M7 11V9.99999C7 8.11437 7 7.17156 7.58579 6.58577C8.05733 6.11423 8.76022 6.02227 10 6.00433");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

</style>
