<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wzhaw1qov"/><path class="jk18robot"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kin-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jk18robot {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 4l7.059 4v8L12 20l-7.059-4V8z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wzhaw1qov {
  fill: var(--svg-color--7e43ff, #7e43ff);
  d: path("M24 0H0v24h24z");
}

</style>
