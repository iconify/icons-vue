<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nplxrbcws"/><path clip-rule="evenodd" class="rh_jqrswi"/><path clip-rule="evenodd" class="b1vqsys4a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:juris-background" /></template>
<style>
.b1vqsys4a {
  fill: var(--svg-color--cc051c, #cc051c);
  fill-rule: evenodd;
  d: path("M11.428 13.224c-.141-.256-.432-.768-.572-1.024c.422-.769 1.285-2.315 1.716-3.083h-2.288L8.567 12.2l1.717 3.083h3.423c1.241-2.242 2.755-4.959 4.005-7.2l-1.145-2.059c-1.258 2.27-2.745 4.94-4.004 7.2h-1.144z");
}

.ft5dv1b6b {
  fill: none;
}

.nplxrbcws {
  fill: var(--svg-color--132452, #132452);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rh_jqrswi {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.856 10.142a2320 2320 0 0 1-4.005 7.2H9.14L6.288 12.2l2.86-5.142h4.568L14.86 5H8.004L4 12.2c.968 1.747 3.019 5.434 3.996 7.2h8L20 12.2z");
}

</style>
