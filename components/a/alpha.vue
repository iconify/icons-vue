<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedAlpha0)" class="h4l2lbcsk"/><path fill="url(#tokenBrandedAlpha1)" class="iqcqclbwr"/><path class="s6t0-zgwz"/><defs><linearGradient id="tokenBrandedAlpha0" x1="12" x2="12" y1="2" y2="22" gradientUnits="userSpaceOnUse"><stop class="on_ex-bnx"/><stop offset=".73" class="znkur0bcb"/></linearGradient><linearGradient id="tokenBrandedAlpha1" x1="5.8" x2="9.852" y1="20.625" y2="3.477" gradientUnits="userSpaceOnUse"><stop class="bydaqlbho"/><stop offset="1" class="s46341bth"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:alpha" /></template>
<style>
.bydaqlbho {
  stop-color: var(--svg-color--f8f8fa, #F8F8FA);
}

.ft5dv1b6b {
  fill: none;
}

.h4l2lbcsk {
  d: path("M12 2v7.481l1.375 3.375L12 11.713v3.593l.043.044A26.8 26.8 0 0 0 20.126 22z");
}

.iqcqclbwr {
  d: path("M12 2v7.481l-1.375 3.375L12 11.713v3.593l-.044.044A26.8 26.8 0 0 1 3.875 22z");
}

.on_ex-bnx {
  stop-color: var(--svg-color--f5f6f8, #F5F6F8);
}

.s46341bth {
  stop-color: var(--svg-color--a6a8bf, #A6A8BF);
}

.s6t0-zgwz {
  fill: var(--svg-color--f5cc02, #F5CC02);
  d: path("M12 20.125a1.875 1.875 0 1 0 0-3.75a1.875 1.875 0 0 0 0 3.75");
}

.znkur0bcb {
  stop-color: var(--svg-color--b6b8cb, #B6B8CB);
}

</style>
