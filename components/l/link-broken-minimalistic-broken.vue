<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jl07vlb8x"/><path class="yh37ftn9n"/><path class="afxk9u7hc"/><path class="rdgy8mlra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-broken-minimalistic-broken" /></template>
<style>
.afxk9u7hc {
  d: path("M6.58787 3L7.50049 5.20521");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl07vlb8x {
  d: path("M10 5.04877L10.367 4.70563C12.7995 2.43146 16.7432 2.43146 19.1757 4.70563M16.9735 15L19.1757 12.9411C20.3438 11.849 20.951 10.4309 20.9972 9");
}

.rdgy8mlra {
  d: path("M3.50189 6.08658L9.04972 8.79453");
}

.yh37ftn9n {
  d: path("M14 18.9278L13.6345 19.2773C11.2123 21.5937 7.25434 21.5644 4.83209 19.248C2.43376 16.9546 2.37639 13.2153 4.74095 10.89L5.64594 10");
}

</style>
