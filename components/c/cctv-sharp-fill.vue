<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="k5ha-2b_m"/><path class="q9gipob_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k5ha-2b_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.4669 2.0729L17.6659 6.1935C18.0439 6.3462 18.2913 6.7131 18.2913 7.1207C18.2913 7.2491 18.2666 7.3763 18.2185 7.4953L15.5963 13.9856C15.4435 14.3636 15.0767 14.611 14.6691 14.611C14.5407 14.611 14.4135 14.5863 14.2945 14.5382L4.0954 10.4175C3.7175 10.2648 3.47 9.898 3.47 9.4903C3.47 9.362 3.4948 9.2348 3.5429 9.1157L6.1651 2.6254C6.3178 2.2475 6.6847 2 7.0923 2C7.2207 2 7.3479 2.0248 7.4669 2.0729Z");
  stroke: none;
}

.q9gipob_j {
  d: path("M16.5421 8.9751L21.0001 8.6191L18.3778 15.1094L15.4183 11.7566M6.788 10.4269L6.788 17L3 17M3 12L3 22");
}

</style>
