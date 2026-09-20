<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGafGdAVqS)" class="r4i437pya"/><path clip-rule="evenodd" class="a_qcezg4a"/><path class="w6qdi3b6o"/><path class="prfl5qbhk"/><path class="isuawrbpk"/></g><defs><linearGradient id="SVGafGdAVqS" x1="19.529" x2="4" y1="12.706" y2="12.941" gradientUnits="userSpaceOnUse"><stop class="z6-379-5g"/><stop offset="1" class="uxra1ra9x"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:equal-background" /></template>
<style>
.a_qcezg4a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.059a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.isuawrbpk {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.118 13.882c-.565 0-.861-.626-.941-.941v.941c0 1.13.941 1.412 1.412 1.412h4.235c0-1.13-.941-1.412-1.412-1.412zm0-3.764c-.565 0-.706.315-.706.47c0 .754.786.942 1.177.942h2.823c1.13 0 1.412.941 1.412 1.412h-4.706c-.565 0-.861-.626-.941-.942V9.647c0-.752.626-.94.941-.94h4.706c0 1.129-.941 1.411-1.412 1.411z");
}

.prfl5qbhk {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.824 8.706h-4.706a.94.94 0 0 0-.941.941v4.236c0 1.13.941 1.412 1.412 1.412h4.235c0-1.13-.941-1.412-1.412-1.412h-.941c-.47 0-1.412 0-1.412-1.883c0-1.505.941-1.882 1.412-1.882h.706c1.317 0 1.647-.941 1.647-1.412");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uxra1ra9x {
  stop-color: var(--svg-color--015bd5, #015bd5);
}

.w6qdi3b6o {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.706 7.53c-1.506 0-4.551.786-5.883 1.177l2.353-2.588v.706c.235-.156 1.224-.47 3.294-.47s4 1.566 4.706 2.352h-.47c-.706-.39-2.495-1.176-4-1.176m-1.412 8.939c1.506 0 4.55-.786 5.882-1.176l-2.353 2.588v-.706c-.235.155-1.223.47-3.294.47s-4-1.567-4.706-2.352h.47c.707.39 2.495 1.176 4 1.176");
}

.z6-379-5g {
  stop-color: var(--svg-color--2dfaee, #2dfaee);
}

</style>
