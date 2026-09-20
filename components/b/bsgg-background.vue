<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t9klgncbm"/><path class="cu7elabfh"/><path class="b2x8vwb3p"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bsgg-background" /></template>
<style>
.b2x8vwb3p {
  fill: var(--svg-color--000, #000);
  d: path("M11.474 8.535a1.07 1.07 0 0 1 .757-.324a1.04 1.04 0 0 1 .758.324l3.857 4c.407.421.632.985.627 1.57a2.3 2.3 0 0 1-.631 1.575l-3.853 3.996a1.07 1.07 0 0 1-.758.324a1.04 1.04 0 0 1-.757-.324a1.12 1.12 0 0 1-.316-.787c0-.294.114-.575.316-.788l3.309-3.583a.597.597 0 0 0 0-.825l-3.31-3.579a1.15 1.15 0 0 1 0-1.579");
}

.cu7elabfh {
  fill: var(--svg-color--000, #000);
  d: path("M12.526 4.324A1.08 1.08 0 0 0 11.768 4a1.04 1.04 0 0 0-.758.324l-3.856 4a2.23 2.23 0 0 0-.628 1.57c.002.587.228 1.15.632 1.575l3.853 3.996a1.05 1.05 0 0 0 1.515 0a1.137 1.137 0 0 0 0-1.575l-3.31-3.583a.6.6 0 0 1 0-.825l3.31-3.579c.206-.212.32-.496.316-.791a1.15 1.15 0 0 0-.316-.788");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t9klgncbm {
  fill: var(--svg-color--f3ce4e, #f3ce4e);
  d: path("M24 0H0v24h24z");
}

</style>
