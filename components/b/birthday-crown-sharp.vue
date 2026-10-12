<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ckek_diwl"/><path class="eke76wb1m"/><path class="sleg5gorn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birthday-crown-sharp" /></template>
<style>
.ckek_diwl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.17 8.6l3.16 2.8l.67.6l.53-.73l2.94-4.04l.53-.73l.53.73l2.94 4.04l.53.73l.67-.6l3.16-2.8l.67-.6l-.11.89l-1.28 10.22L19 20H5l-.11-.89L3.61 8.89L3.5 8z");
}

.eke76wb1m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.16 13.12l.36.83l.16.37l.39.04l.91.08l.4.04l-.3.26l-.69.6l-.3.27l.09.39l.2.88l.09.39l-.34-.2l-.79-.47l-.34-.2l-.34.2l-.79.47l-.34.2l.09-.39l.2-.88l.09-.39l-.3-.27l-.69-.6l-.3-.26l.4-.04l.91-.08l.39-.04l.16-.37l.36-.83l.16-.37z");
}

.sleg5gorn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 5h.01M12 3.75h.01M20.5 5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
