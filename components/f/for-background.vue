<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lr1i1xpuk"/><path class="v-79j6oug"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:for-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lr1i1xpuk {
  fill: var(--svg-color--49c5ab, #49c5ab);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v-79j6oug {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.657 18.766v-7.968C7.657 7.045 10.734 4 14.523 4h.563a1.253 1.253 0 0 1 1.257 1.248c0 .686-.562 1.038-1.257 1.038h-.76c-2.308 0-4.383 2.057-4.383 4.343v.685h5.207a1.17 1.17 0 0 1 1.193 1.143c0 .631-.535 1.143-1.193 1.143H9.943v5.166C9.943 19.45 9.486 20 8.8 20s-1.143-.549-1.143-1.234");
}

</style>
