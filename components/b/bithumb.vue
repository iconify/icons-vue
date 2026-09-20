<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iuw8a3bwn"/><path class="rcv517bhj"/><path fill="url(#SVG7h9suQwL)" class="z_nfh9b9o"/><defs><linearGradient id="SVG7h9suQwL" x1="18.231" x2="13.097" y1="15.912" y2="8.033" gradientUnits="userSpaceOnUse"><stop offset=".41" class="p60z8pb_l"/><stop offset=".5" class="ezzsq_bps"/><stop offset=".62" class="w9uu5hkbb"/><stop offset=".75" class="ykw_02n3y"/><stop offset=".81" class="otimhqd8g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bithumb" /></template>
<style>
.ezzsq_bps {
  stop-color: var(--svg-color--f16d21, #f16d21);
}

.ft5dv1b6b {
  fill: none;
}

.iuw8a3bwn {
  fill: var(--svg-color--d53127, #d53127);
  d: path("M6.007 7.287h2.562L6.577 12.16s-1.042-.017-1.36-.927a1.44 1.44 0 0 1-.022-.835z");
}

.otimhqd8g {
  stop-color: var(--svg-color--d53127, #d53127);
}

.p60z8pb_l {
  stop-color: var(--svg-color--f47320, #f47320);
}

.rcv517bhj {
  fill: var(--svg-color--f47320, #f47320);
  d: path("m15.944 7.391l-3.258-.057l.733-2.418A1.483 1.483 0 0 0 12.005 3H9.03l-3.4 12.21s-1.218 5.222 3.4 5.695c0 0 7.3 1.492 9.643-7.329c0 0 1.236-5.335-2.73-6.185m-2.227 6.056s-.13 2.253-1.83 2.648a1.1 1.1 0 0 1-.75-.077c-.266-.136-.54-.418-.534-1.01q.006-.256.082-.504l.627-2.344h1.714s.776.252.691 1.287");
}

.w9uu5hkbb {
  stop-color: var(--svg-color--e95c22, #e95c22);
}

.ykw_02n3y {
  stop-color: var(--svg-color--dc4125, #dc4125);
}

.z_nfh9b9o {
  d: path("M18.83 11.117c-.312-3.584-2.886-3.726-2.886-3.726l-3.258-.057l-1.4 4.854h1.71c.313.017.885.535.7 1.452");
}

</style>
