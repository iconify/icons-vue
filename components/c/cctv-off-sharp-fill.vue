<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="ji42g9sdm"/><path class="xw9j-tsbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ji42g9sdm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.6092 14.6092C14.5011 14.6027 14.3948 14.5788 14.2945 14.5382L4.0954 10.4175C3.7175 10.2648 3.47 9.898 3.47 9.4903C3.47 9.362 3.4948 9.2348 3.5429 9.1157L5.1465 5.1465L14.6092 14.6092ZM6.2018 2.545C6.3728 2.2105 6.7167 2 7.0923 2C7.2207 2 7.3479 2.0248 7.4669 2.0729L17.6659 6.1935C18.0439 6.3462 18.2913 6.7131 18.2913 7.1207C18.2913 7.2491 18.2666 7.3763 18.2185 7.4953L16.1851 12.5282L6.2018 2.545Z");
  stroke: none;
}

.xw9j-tsbp {
  d: path("M16.5421 8.9751L21.0001 8.6191L18.6905 14.3355M6.788 10.4269L6.788 17L3 17M3 12L3 22M1.7071 1.7071L22.2929 22.2929");
}

</style>
