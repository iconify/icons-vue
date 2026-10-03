<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wrcowbcuv"/><path class="a dz4dytb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-tsdoc" /></template>
<style>
.dz4dytb-q {
  fill: var(--svg-color--108938, #108938);
  d: path("M29.03 2H2.97a.97.97 0 0 0-.97.97v26.06a.97.97 0 0 0 .97.97h26.06a.97.97 0 0 0 .97-.97V2.97a.97.97 0 0 0-.97-.97M26.5 22.2l-1.43 2.47l-3.6-2.55l.4 4.38H18.9l.4-4.38l-3.6 2.55l-1.44-2.47l4.02-1.82l-4.02-1.83l1.45-2.47l3.59 2.55l-.4-4.38h2.99l-.42 4.38l3.6-2.55l1.44 2.47l-4 1.82z");
}

.wrcowbcuv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: bevel;
  stroke-width: var(--svg-stroke-width--1-06px, 1.06px);
  d: path("M14.61 14.64h11.44v11.44H14.61z");
}

</style>
