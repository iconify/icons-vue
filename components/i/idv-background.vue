<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qvfchd73u"/><path class="mrgto-_qn"/><path class="ovgg3abnw"/><path clip-rule="evenodd" class="yg8h30b0f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:idv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mrgto-_qn {
  fill: var(--svg-color--000, #000);
  d: path("M9.82 8.545h-.728v2.073a2.91 2.91 0 1 0 .073 3.76l-.39-.702a2.182 2.182 0 1 1 .288-1.495h.756zm7.272 6.91a2.909 2.909 0 1 0-2.237-4.771l.411.666a2.182 2.182 0 1 1-.356 1.123l-.582-.836a2.9 2.9 0 0 0-.145.909v2.909h.727v-.982a2.9 2.9 0 0 0 2.182.982");
}

.ovgg3abnw {
  fill: var(--svg-color--000, #000);
  d: path("M4.023 12.18a2.909 2.909 0 0 0 5.142 2.2l-.39-.705a2.182 2.182 0 0 1-4.018-1.494z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qvfchd73u {
  fill: var(--svg-color--1ebcff, #1ebcff);
  d: path("M24 0H0v24h24z");
}

.yg8h30b0f {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12.002 15.455a2.91 2.91 0 1 0 0-5.819a2.91 2.91 0 0 0 0 5.82m0-.727a2.182 2.182 0 1 0 0-4.365a2.182 2.182 0 0 0 0 4.365");
}

</style>
