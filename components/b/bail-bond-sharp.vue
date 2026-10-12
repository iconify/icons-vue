<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jq-fgxcpx"/><path class="gn79dk-ff"/><path class="q02-ao_6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bail-bond-sharp" /></template>
<style>
.gn79dk-ff {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 8.75l-.667-1H5.75v1.5c0 2 4 1 4 3v1.5H6.417l-.667-1m2-6.5v1.5m0 6v1.5m8.25.5V13h4v2.75m-5.25 0h6.5v5.5h-6.5z");
}

.jq-fgxcpx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h11V11h-3.5v10.25h-9.5V2.75z");
}

.q02-ao_6j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 18.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
