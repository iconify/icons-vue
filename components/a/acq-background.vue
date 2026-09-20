<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="golr_2uju"/><path clip-rule="evenodd" class="a_qcezg4a"/><path class="cqaz39wdx"/><path class="drkjkwb2j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:acq-background" /></template>
<style>
.a_qcezg4a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.059a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.cqaz39wdx {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.412 12.235v.706H7.294l3.53-5.647l1.882 3.059h-.941l-.942-1.647l-2.117 3.529z");
}

.drkjkwb2j {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.059 11.765v-.706h6.117l-3.53 5.647l-1.881-3.058h.94l.942 1.647l2.117-3.53z");
}

.ft5dv1b6b {
  fill: none;
}

.golr_2uju {
  fill: var(--svg-color--44b4ac, #44b4ac);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
