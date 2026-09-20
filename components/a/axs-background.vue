<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGj1JzybKV)" class="r4i437pya"/><path class="r_szz51aa"/></g><defs><linearGradient id="SVGj1JzybKV" x1="12" x2="12" y1="6.354" y2="17.646" gradientUnits="userSpaceOnUse"><stop class="fza6mobwn"/><stop offset="1" class="x10ubcctn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:axs-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fza6mobwn {
  stop-color: var(--svg-color--00d2f7, #00d2f7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r_szz51aa {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.602 7.119c.546-.701 4.626 1.53 6.702 3.459a.23.23 0 0 1-.014.348l-.66.55a.236.236 0 0 1-.286.01l-1.356-.974l-1.619 1.723c-.16.164-.447.513-.644.371a.895.895 0 0 1-.245-1.011c.254-.589 1.605-1.822 1.605-1.822c-.678-.541-2.071-1.05-2.316.673c-.16 1.12-.122 5.718 1.836 4.612c1.882-1.068 9.389-9.384 10.89-8.66c1.502.72 2.024 8.66.9 10.1c-.368.471-2.815.17-6.707-3.115a.236.236 0 0 1-.015-.344l.66-.644a.236.236 0 0 1 .329-.005c.885.772 4.108 3.247 4.457 1.586c.23-1.11.254-6.038-.871-5.676c-.612.198-1.694 1.073-2.504 1.765C12.99 11.57 6.791 18.38 5.35 17.58c-1.44-.796-1.788-9.13-.753-10.462z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.x10ubcctn {
  stop-color: var(--svg-color--004cdc, #004cdc);
}

</style>
