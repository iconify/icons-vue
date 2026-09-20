<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfuxMdG9m)" class="r4i437pya"/><path class="c1q1uwdfx"/></g><defs><linearGradient id="SVGfuxMdG9m" x1="18.934" x2="5.749" y1="6.714" y2="17.643" gradientUnits="userSpaceOnUse"><stop class="mvv2i2b7u"/><stop offset="1" class="rvt77lvmf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:divi-background" /></template>
<style>
.c1q1uwdfx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.763 4H4c1.115 2.587 2.57 3.733 4.379 3.733h4.176c1.669 0 3.546 2.112 3.546 4.267s-1.877 4.267-3.546 4.267H9.333v-4.768H5.5V20h7.264C16.309 20 20 17.392 20 12s-3.69-8-7.237-8");
}

.ft5dv1b6b {
  fill: none;
}

.mvv2i2b7u {
  stop-color: var(--svg-color--ec1f55, #ec1f55);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rvt77lvmf {
  stop-color: var(--svg-color--ec2928, #ec2928);
}

</style>
