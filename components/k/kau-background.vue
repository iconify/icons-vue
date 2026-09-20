<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ze9x4patj"/><path class="qxc7qfb2v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kau-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qxc7qfb2v {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.258 9.677L9.16 12.774l4.191 6.348a2.22 2.22 0 0 0 1.796.878H20a9.8 9.8 0 0 1-2.065-2.065zM4 4h4.645v8.975L4 17.42zm9.29 0h4.13l-4.13 4.129z");
}

.ze9x4patj {
  fill: var(--svg-color--857550, #857550);
  d: path("M24 0H0v24h24z");
}

</style>
