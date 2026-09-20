<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGpd5NZciy)" clip-rule="evenodd" class="d8eg2wfte"/><defs><linearGradient id="SVGpd5NZciy" x1="6.915" x2="17.06" y1="17.225" y2="9.145" gradientUnits="userSpaceOnUse"><stop class="jggj2ub1v"/><stop offset="1" class="oz9227rbr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eden" /></template>
<style>
.d8eg2wfte {
  fill-rule: evenodd;
  d: path("M16.68 9.63L13 6.075v7.115zm-7.54 7.535l1.86-1.8v-.07L7.04 11.47v3.67zm1.09 1.055l.77-.745V21h2v-3.5l1.55 1.5v-.01l.3.29l3.635-3.515h.015V9.25h-.03l-5.38-5.2L12 3L5.53 9.25H5.5v6.515h.015L8.05 18.22l1.085 1.055h.01l1.09-1.05zM13 15.4l1.85 1.785L17 15.1v-3.67l-4 3.865zM7.32 9.63L11 13.19V6.075z");
}

.ft5dv1b6b {
  fill: none;
}

.jggj2ub1v {
  stop-color: var(--svg-color--10cb88, #10cb88);
}

.oz9227rbr {
  stop-color: var(--svg-color--bdf418, #bdf418);
}

</style>
