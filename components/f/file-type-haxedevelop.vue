<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.34 .34)scale(.97892)"><defs><linearGradient id="SVGSQNJybqi" x1="16" x2="16" y1="2.04" y2="30" gradientUnits="userSpaceOnUse"><stop offset="0" class="ve_g0xbpo"/><stop offset="1" class="bcuiffgri"/></linearGradient></defs><path fill="url(#SVGSQNJybqi)" class="iu0_bvb-e"/><g class="v27f9cbzg"><path class="pss9pdbrp"/><path class="oijf4kb3e"/></g><g class="v27f9cbzg"><path class="hahcdrhdp"/><path class="llx3pobjy"/></g><path class="rydf30b_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-haxedevelop" /></template>
<style>
.bcuiffgri {
  stop-color: var(--svg-color--2781c4, #2781c4);
}

.hahcdrhdp {
  d: path("M16 2.04h.09v27.9H16Zm12.5 0h.09v27.9h-.09Zm-25.1 0h.09v27.9H3.4Z");
}

.iu0_bvb-e {
  d: path("M30 30H2.04V2.04H30V16Z");
}

.llx3pobjy {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-dasharray: 0.038 .412;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-09px, 0.09px);
  d: path("M19.14 2.05v27.9m3.14-27.9v27.9m3.14-27.9v27.9M12.86 2.05v27.91M9.72 2.05v27.9M6.58 2.05v27.9");
}

.oijf4kb3e {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-dasharray: 0.037 .413;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-09px, 0.09px);
  d: path("M2.05 12.86h27.9M2.06 6.58h27.9M2.06 9.72h27.9m-27.9 9.42h27.91M2.05 22.28h27.91M2.05 25.42h27.91");
}

.pss9pdbrp {
  d: path("M2.04 16h27.9v.09H2.04Zm.01-12.61h27.9v.09H2.05Zm0 25.11h27.9v.09H2.05Z");
}

.rydf30b_j {
  fill: var(--svg-color--fff, #fff);
  d: path("M29.3 26.4H2.7v.7h26.6ZM16 6.1V4.81L3 26.41h.83Zm-8.2 8.02l-.74-.52l-4.34 12.8h.83ZM16 6.1V4.81l-8.94 8.78l.74.52Zm12.2 20.3h.83l-13-21.6v1.29Zm.28 0h.86l-4.37-12.8l-.75.52Zm-4.26-12.3l.74-.52l-8.94-8.78v1.29Zm-7.14 8.61H7.82v-.93h9.26Zm-5.56 1.39H6.66v.93h4.86Zm9.48 0h-8.1v.93H21Zm4.63 0h-3.48v.93h3.48Zm-1.39-2.33h-5.79v.93h5.8Z");
}

.v27f9cbzg {
  fill: var(--svg-color--fff, #fff);
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ve_g0xbpo {
  stop-color: var(--svg-color--459fe2, #459fe2);
}

</style>
