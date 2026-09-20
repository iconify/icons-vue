<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q3evsfmbn"/><path class="ph4pbdw4i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:get-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ph4pbdw4i {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.5 11V9.5L10 12l2.5 2.5V13h4.532l-4.803 4.646L6.42 12l5.807-5.646l3.076 2.991c.188.183.444.285.71.285s.52-.102.709-.285a.96.96 0 0 0 .294-.69a.96.96 0 0 0-.294-.689l-3.785-3.68a1.02 1.02 0 0 0-.71-.286a1.02 1.02 0 0 0-.709.285L4.294 11.31a.96.96 0 0 0 0 1.38l7.225 7.024a1.02 1.02 0 0 0 1.419 0l6.611-6.428c.274-.26.451-.595.451-.987c0-.393-.177-.728-.46-.996a1.04 1.04 0 0 0-.7-.303z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q3evsfmbn {
  fill: var(--svg-color--01c696, #01c696);
  d: path("M24 0H0v24h24z");
}

</style>
