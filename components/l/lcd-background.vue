<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="hanwe_b8x"/><path class="r0k3uj_mg"/><path class="ziyz7oduv"/><path class="fszzipbul"/><path class="sauzpcb9s"/><path class="atytt7mak"/><path class="ce9k-ccgj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lcd-background" /></template>
<style>
.atytt7mak {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M12 17.784a5.784 5.784 0 1 0 0-11.567a5.784 5.784 0 0 0 0 11.567");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ce9k-ccgj {
  fill: var(--svg-color--2a28f5, #2a28f5);
  d: path("M9.647 12.108v3.186h4.706v-1.412h-2.824v-1.247a8.8 8.8 0 0 1-1.882-.527m0-1.285a19 19 0 0 0 1.882.603v-3.19H9.647z");
}

.fszzipbul {
  fill: var(--svg-color--c4c5fb, #c4c5fb);
  d: path("M12 18.974a6.974 6.974 0 1 0 0-13.949a6.974 6.974 0 0 0 0 13.949");
}

.ft5dv1b6b {
  fill: none;
}

.hanwe_b8x {
  fill: var(--svg-color--4747f3, #4747f3);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r0k3uj_mg {
  fill: var(--svg-color--7c7cf4, #7c7cf4);
  d: path("M12 19.698a7.699 7.699 0 1 0 0-15.397a7.699 7.699 0 0 0 0 15.397");
}

.sauzpcb9s {
  fill: var(--svg-color--e0e0fc, #e0e0fc);
  d: path("M12 18.518a6.518 6.518 0 1 0 0-13.036a6.518 6.518 0 0 0 0 13.036");
}

.ziyz7oduv {
  fill: var(--svg-color--a2a2f8, #a2a2f8);
  d: path("M12 19.364a7.365 7.365 0 1 0 0-14.73a7.365 7.365 0 0 0 0 14.73");
}

</style>
