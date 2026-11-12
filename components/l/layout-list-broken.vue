<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xuny64b0w"/><path class="zzoug-3hz"/><path class="jm1dfw2ei"/><path class="aqn8_gw_r"/><path class="yn4ftnbvf"/><path class="mocjfac8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layout-list-broken" /></template>
<style>
.aqn8_gw_r {
  d: path("M3.07031 4.51951C3.13628 4.06595 3.26431 3.74414 3.51273 3.49572C4.02529 2.98315 4.85025 2.98315 6.50017 2.98315C8.15008 2.98315 8.97504 2.98315 9.48761 3.49572C10.0002 4.00828 10.0002 4.83324 10.0002 6.48315C10.0002 8.13307 10.0002 8.95803 9.48761 9.47059C8.97504 9.98315 8.15008 9.98315 6.50017 9.98315C4.85025 9.98315 4.02529 9.98315 3.51273 9.47059C3.28275 9.24061 3.15596 8.94775 3.08606 8.54569");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm1dfw2ei {
  d: path("M21 20.0171H14");
}

.mocjfac8k {
  d: path("M21 8.98315H14");
}

.xuny64b0w {
  d: path("M10 19.4468C9.93403 19.9004 9.80601 20.2222 9.55758 20.4706C9.04502 20.9832 8.22006 20.9832 6.57014 20.9832C4.92023 20.9832 4.09527 20.9832 3.58271 20.4706C3.07014 19.958 3.07014 19.1331 3.07014 17.4832C3.07014 15.8332 3.07014 15.0083 3.58271 14.4957C4.09527 13.9832 4.92023 13.9832 6.57015 13.9832C8.22006 13.9832 9.04502 13.9832 9.55758 14.4957C9.78756 14.7257 9.91435 15.0186 9.98425 15.4206");
}

.yn4ftnbvf {
  d: path("M21 3.98315L14 3.98315");
}

.zzoug-3hz {
  d: path("M21 15.0171H14");
}

</style>
