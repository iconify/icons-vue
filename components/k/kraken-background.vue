<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="l33e9mlzu"/><path class="yxctgibqq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kraken-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l33e9mlzu {
  fill: var(--svg-color--7133f5, #7133f5);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yxctgibqq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.998 5.333C7.581 5.333 4 9.133 4 13.82v3.637c0 .669.511 1.21 1.142 1.21s1.145-.541 1.145-1.21V13.82c0-.67.51-1.213 1.142-1.213c.63 0 1.142.542 1.142 1.213v3.637c0 .669.51 1.21 1.142 1.21s1.143-.541 1.143-1.21V13.82c0-.67.511-1.213 1.142-1.213c.633 0 1.146.542 1.146 1.213v3.637c0 .669.51 1.21 1.141 1.21s1.142-.541 1.142-1.21V13.82c0-.67.511-1.213 1.146-1.213c.63 0 1.142.542 1.142 1.213v3.637c0 .669.51 1.21 1.143 1.21c.631 0 1.142-.541 1.142-1.21V13.82c0-4.686-3.583-8.486-8.002-8.486");
}

</style>
