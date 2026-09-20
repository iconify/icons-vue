<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGdke5Vcgq)" class="r4i437pya"/><path class="p31ouhbxx"/></g><defs><linearGradient id="SVGdke5Vcgq" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="f_446jbjz"/><stop offset="1" class="mu22hj6pw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bcdt-background" /></template>
<style>
.f_446jbjz {
  stop-color: var(--svg-color--07b5f3, #07b5f3);
}

.ft5dv1b6b {
  fill: none;
}

.mu22hj6pw {
  stop-color: var(--svg-color--44e6dc, #44e6dc);
}

.p31ouhbxx {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.105 7.352v6.652l3.369 1.962v3.89c0 .11.172.177.27.127L12 18.733l2.223 1.246a.146.146 0 0 0 .22-.127v-3.886l3.452-1.962V7.352L12 4zM8.552 8.5L6.69 7.461L12 4.383l5.262 3.032l-1.84 1.057S13.145 7.192 12 6.535zm-2.025 5.305V7.848l1.684.944v3.957s2.433 1.272 3.579 1.908v3.734l-1.895 1.045v-3.689l-3.368-1.945zm10.947-6.033v6.029l-3.407 1.945v3.689l-1.877-1.04V14.66c1.14-.64 3.6-1.907 3.6-1.907v-4.02zM8.632 12.53V9.036l3.158 1.755v3.466zm6.736-3.54v3.536l-3.157 1.73v-3.465zM12 10.441L8.926 8.716l3.053-1.748l3.053 1.73z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
