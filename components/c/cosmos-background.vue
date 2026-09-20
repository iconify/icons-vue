<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="h9223gb7j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cosmos-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h9223gb7j {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.95 8.719L8.782 13.88a4.1 4.1 0 0 1-.451-1.895q0-.79.27-1.492q.27-.705.751-1.222q.48-.517 1.154-.82q.674-.3 1.478-.301a3.55 3.55 0 0 1 1.966.569m-.456 6.83q-.673.3-1.479.301a3.55 3.55 0 0 1-1.965-.569l5.168-5.16q.1.193.18.402q.271.705.271 1.493a4.1 4.1 0 0 1-.27 1.492q-.271.703-.751 1.221t-1.154.82m.782 1.6a5.7 5.7 0 0 0 1.796-1.214a5.4 5.4 0 0 0 1.177-1.786q.418-1.02.418-2.164a5.65 5.65 0 0 0-1.029-3.283L20 5.345L18.664 4.01l-3.372 3.367a5.7 5.7 0 0 0-.985-.535q-1.038-.44-2.292-.44t-2.291.448a5.7 5.7 0 0 0-1.796 1.214A5.4 5.4 0 0 0 6.75 9.85a5.7 5.7 0 0 0-.418 2.165a5.66 5.66 0 0 0 1.028 3.283L4 18.655l1.336 1.334l3.371-3.367q.455.309.986.535q1.037.44 2.291.44t2.292-.448");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
