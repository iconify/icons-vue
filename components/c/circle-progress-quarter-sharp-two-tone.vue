<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gwxx9runy"/><path class="sun2akb8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-quarter-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gwxx9runy {
  stroke-opacity: 0.4;
  d: path("M3.322 6.9312L3.9098 6.1222C4.5266 5.2732 5.2732 4.5266 6.1222 3.9098L6.9312 3.322M9.448 2.2796L10.4357 2.1231C11.4721 1.959 12.5279 1.959 13.5643 2.1231L14.552 2.2796M17.0688 3.3221L17.8778 3.9098C18.7268 4.5266 19.4734 5.2732 20.0902 6.1222L20.678 6.9312M21.7205 9.448L21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643L21.7205 14.552M20.678 17.0688L20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902L17.0688 20.678");
}

.sun2akb8v {
  d: path("M13 22L12 22C6.4771 22 2 17.5229 2 12L2 11");
}

</style>
