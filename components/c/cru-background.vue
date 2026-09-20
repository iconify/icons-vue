<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f-uihrowy"/><path class="q5sdd7ber"/><path class="nra-m_b3w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cru-background" /></template>
<style>
.f-uihrowy {
  fill: var(--svg-color--f98a16, #f98a16);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.nra-m_b3w {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.685 4.1a.82.82 0 0 1 .782 0l4.098 2.276c.018.017.044.03.08.053c.773.44.622.76.387.978q-.687.68-1.334 1.4l-.31.333c-.197.21-.48.142-.734.018l-.267-.151l-.213-.125v.005l-1.707-.951a.82.82 0 0 0-.782 0c-2.33 1.293-4.578 2.622-6.907 3.929V8.37c0-.266.15-.52.39-.653l6.517-3.622z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q5sdd7ber {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.774 17.5l-4.307 2.4a.82.82 0 0 1-.782 0l-6.516-3.627a.76.76 0 0 1-.391-.653v-3l3.555-1.956v3.022c0 .267.134.52.378.654l2.974 1.715a.81.81 0 0 0 .782 0l1.84-1.022c.467-.2.853-.147 1.102.009l.676.658l.769.742c.4.387.23.827-.08 1.058");
}

</style>
