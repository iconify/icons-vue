<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGaL8Tkebx)" class="y2ec_u10r"/><defs><linearGradient id="SVGaL8Tkebx" x1="19.2" x2="19.2" y1="10.2" y2="13.8" gradientUnits="userSpaceOnUse"><stop class="r2dnp3wpl"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cope" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.r2dnp3wpl {
  stop-color: var(--svg-color--b8b8b8, #b8b8b8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.y2ec_u10r {
  d: path("M3 12a1.8 1.8 0 1 1 3.6 0A1.8 1.8 0 0 1 3 12m7.2 0a1.8 1.8 0 1 1 3.6 0a1.8 1.8 0 0 1-3.6 0m9-1.8a1.8 1.8 0 1 0 0 3.599a1.8 1.8 0 0 0 0-3.599");
}

</style>
