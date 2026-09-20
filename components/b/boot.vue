<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nr8wmpq_p"/><path fill="url(#tokenBrandedBoot0)" class="dg6wtbb5n"/><defs><linearGradient id="tokenBrandedBoot0" x1="12" x2="12" y1="3.25" y2="20.75" gradientUnits="userSpaceOnUse"><stop class="v64-gbcrs"/><stop offset=".56" class="bhwc-_k1f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:boot" /></template>
<style>
.bhwc-_k1f {
  stop-color: var(--svg-color--00a200, #00A200);
}

.dg6wtbb5n {
  fill-opacity: var(--svg-fill-opacity--0-61, 0.61);
  d: path("M12 20.75a8.75 8.75 0 1 0 0-17.5a8.75 8.75 0 0 0 0 17.5");
}

.ft5dv1b6b {
  fill: none;
}

.nr8wmpq_p {
  fill: var(--svg-color--00a200, #00A200);
  d: path("M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2S2 6.477 2 12s4.477 10 10 10");
}

.v64-gbcrs {
  stop-color: var(--svg-color--7dff7d, #7DFF7D);
}

</style>
