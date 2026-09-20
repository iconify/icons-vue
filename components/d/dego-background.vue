<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="v2_u8bbdz"/><path class="hm5wtr9mh"/><path class="p2cjiybbb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dego-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hm5wtr9mh {
  fill: var(--svg-color--fff, #fff);
  d: path("M5 4h3.5v3.5H5zm10.5 0L19 7.5h-3.5zm0 16l3.5-3.5h-3.5zm-7-16h7v3.5h-7zM5 16.5h10.5V20H5zm0-9h3.5v4H5zm10.5 0H19v9h-3.5z");
}

.p2cjiybbb {
  fill: var(--svg-color--fff, #fff);
  d: path("M5 11h3.5v5.5H5z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v2_u8bbdz {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M24 0H0v24h24z");
}

</style>
