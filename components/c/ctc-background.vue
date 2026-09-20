<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="p56ll-bxp"/><path class="rkejr1zby"/><path class="j4hxujpxt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j4hxujpxt {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.5 13.505a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.p56ll-bxp {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.4 9.02l-1.795.55a5.46 5.46 0 0 0-5.085-3.065C7.66 6.505 6 9.8 6 12c0 1.735 1.23 5.505 5.5 5.505c3.195 0 4.89-2.565 5.105-3.02l1.895.45c-.175.685-2.325 4.56-6.98 4.56C7.37 19.495 4 16.14 4 12s3.37-7.495 7.52-7.495c4.155 0 6.47 3.2 6.88 4.515");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rkejr1zby {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.445 11.005H20v2h-7.555z");
}

</style>
