<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="w7vbp5bbt"/><path class="pjscojb_i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:abr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.pjscojb_i {
  fill: var(--svg-color--fff, #fff);
  d: path("M7 4.91c0-.5.4-.91.895-.91a.9.9 0 0 1 .89.91v3.26A5 5 0 0 1 17 12v7.09c0 .5-.4.91-.895.91a.9.9 0 0 1-.89-.91v-3.26A5 5 0 0 1 7 12zM8.785 12a3.215 3.215 0 1 0 0-.02z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w7vbp5bbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.01 5c0-.49.4-1 .9-1c4.04 0 7.835 2.655 8.09 6.905v6.205c0 .49-.5.89-1 .89s-1-.4-1-.89v-6.15C17.78 7.63 15.25 6 12 6c-.5 0-.99-.51-.99-1m1.98 14c0 .49-.4 1-.9 1c-4.04 0-7.835-2.655-8.09-6.905V6.89C4 6.4 4.5 6 5 6s1 .4 1 .89v6.15C6.22 16.37 8.75 18 12 18c.5 0 .99.51.99 1");
}

</style>
