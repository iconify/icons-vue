<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGBRCJseAc)" class="vcfl6nbtq"/><defs><linearGradient id="SVGBRCJseAc" x1="4.103" x2="19.948" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="xm2s_acyl"/><stop offset=".48" class="k96bt45ga"/><stop offset="1" class="ky09lxb2t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gxa" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k96bt45ga {
  stop-color: var(--svg-color--a472ff, #a472ff);
}

.ky09lxb2t {
  stop-color: var(--svg-color--543fff, #543fff);
}

.vcfl6nbtq {
  d: path("M12 18.75a6.85 6.85 0 0 1-6.71-5.625H3C3.613 17.569 7.506 21 12 21s8.387-3.431 9-7.875h-2.29A6.85 6.85 0 0 1 12 18.75m0-13.5a6.86 6.86 0 0 1 6.412 4.5h-2.486a4.51 4.51 0 0 0-3.954-2.233C9.592 7.562 7.506 9.598 7.5 12a4.607 4.607 0 0 0 4.472 4.5a4.52 4.52 0 0 0 4.421-3.375h-4.112a2.22 2.22 0 0 1 0-2.25H21C20.387 6.431 16.494 3 12 3s-8.387 3.431-9 7.875h2.29C5.851 7.657 8.731 5.233 12 5.25");
}

.xm2s_acyl {
  stop-color: var(--svg-color--13efcf, #13efcf);
}

</style>
