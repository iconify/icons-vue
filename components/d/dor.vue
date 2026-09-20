<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cerwxzxwb"/><path class="qtawm8l-j"/><path class="lbzobsb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dor" /></template>
<style>
.cerwxzxwb {
  fill: var(--svg-color--128bf4, #128bf4);
  d: path("M6.315 15.232L12.01 9.63l5.675 5.602L12.01 21z");
}

.ft5dv1b6b {
  fill: none;
}

.lbzobsb_k {
  fill: var(--svg-color--1c4387, #1c4387);
  d: path("m9.637 11.969l2.364 2.4l2.371-2.408l.796.789L12 15.988L8.824 12.76z");
}

.qtawm8l-j {
  fill: var(--svg-color--e21639, #e21639);
  d: path("M6.315 8.603L12.01 3l5.675 5.602L12 14.37z");
}

</style>
