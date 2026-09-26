<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jq5l_kbjy"/><path class="fatg9mbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-three-quarter-sharp-duotone" /></template>
<style>
.fatg9mbts {
  d: path("M13 22L12 22C6.4771 22 2 17.5229 2 12C2 6.4771 6.4771 2 12 2C17.5228 2 22 6.4771 22 12L22 13");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jq5l_kbjy {
  stroke-opacity: 0.4;
  d: path("M20.678 17.0688L20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902L17.0688 20.678");
}

</style>
