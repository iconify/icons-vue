<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nzod8xgop"/><path class="b6qin7rlv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:citrea-background" /></template>
<style>
.b6qin7rlv {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 10.183c-.368 0-.735-.183-1.011-.551L8.23 4.85h7.448L12.92 9.632c-.184.368-.552.551-1.012.551zm2.575 1.471c-.368 0-.736-.184-1.012-.552a1.17 1.17 0 0 1 0-1.103l2.759-4.782L20 11.654h-5.517zm-6.253 7.448l2.758-4.781c.184-.368.552-.552 1.012-.552s.736.184 1.011.552l2.759 4.781zm5.241-5.057a1.17 1.17 0 0 1 0-1.104c.184-.367.552-.551 1.012-.551H20l-3.678 6.436zM4 11.654l3.678-6.437L10.437 10q.276.552 0 1.103c-.184.368-.552.552-1.012.552zm0 .736h5.517c.368 0 .736.184 1.012.551q.276.552 0 1.104L7.77 18.826L4.092 12.39z");
}

.ft5dv1b6b {
  fill: none;
}

.nzod8xgop {
  fill: var(--svg-color--fd7f00, #fd7f00);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
