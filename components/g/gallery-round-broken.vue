<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="de9gu_b1y"/><path class="kg-2ylb5o"/><path class="eqv3evbyx"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-round-broken" /></template>
<style>
.de9gu_b1y {
  cx: 16px;
  cy: 8px;
  r: 2px;
}

.eqv3evbyx {
  d: path("M22.0005 13.3846L21.0271 13.2498C18.1834 12.8561 15.6103 14.2718 14.2852 16.5001");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kg-2ylb5o {
  d: path("M2 10.1538L2.98073 10.013C9.95896 9.01099 15.9238 15.0313 14.8571 22");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

</style>
