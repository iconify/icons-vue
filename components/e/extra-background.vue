<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="a_cfr3bpj"/><path clip-rule="evenodd" class="ubh98c8di"/><path class="t_lebhb5i"/><path class="rusewb-pu"/><path class="uidrtfb5t"/><path class="daacanp5m"/><path class="p3cabyb3r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:extra-background" /></template>
<style>
.a_cfr3bpj {
  fill: var(--svg-color--146ae5, #146ae5);
  d: path("M24 0H0v24h24z");
}

.daacanp5m {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.62 13.564l.587.856l.55-.739l-.663-.757l-.47.64z");
}

.ft5dv1b6b {
  fill: none;
}

.p3cabyb3r {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.497 15.765L12 11.06h1.242l3.464 4.706z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rusewb-pu {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.718 12.471c.33.198.847.377 1.426.264c.513-.104.056-.518-.551-.913a2 2 0 0 0-.875.65");
}

.t_lebhb5i {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.567 15.764v-1.148h-2.25a.893.893 0 0 1-.894-.903c0-.494.405-1.007.895-1.007h1.74v-1.022h-1.74a2.03 2.03 0 0 0-1.874 1.263c-.1.248-.152.513-.15.78a2.03 2.03 0 0 0 2.024 2.037z");
}

.ubh98c8di {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.941a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12");
}

.uidrtfb5t {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.567 8.706v1.149h-2.25a.893.893 0 0 0-.894.903c0 .494.405.772.894.772h1.742v1.176H9.317a1.96 1.96 0 0 1-2.023-1.962a2.03 2.03 0 0 1 2.023-2.038zm1.642 7.06l3.497-4.707h-1.243L12 15.765z");
}

</style>
