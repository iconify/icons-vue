<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e-w3a0tlt"/><path class="acxaosb8x"/><path class="rnl0wu09u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:10set-background" /></template>
<style>
.acxaosb8x {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.822 11.278s.47-.433.47-.739a.5.5 0 0 0-.155-.367l-2.766-2.724a.53.53 0 0 0-.743 0l-2.766 2.724a.5.5 0 0 0-.155.362c0 .31.47.744.47.744v4.746s-.47.428-.47.739a.5.5 0 0 0 .155.362l2.766 2.724a.53.53 0 0 0 .743 0l2.766-2.724a.5.5 0 0 0 .155-.362c0-.31-.47-.739-.47-.739zm-1.881 4.38a.5.5 0 0 1-.156.366l-.785.87l-.786-.87a.52.52 0 0 1-.155-.367v-4.012c0-.142.056-.269.155-.367l.786-.87l.785.87c.1.094.155.23.155.367z");
}

.e-w3a0tlt {
  fill: var(--svg-color--fd62d5, #fd62d5);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rnl0wu09u {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.965 6.512L15.48 4.146A.54.54 0 0 0 15.114 4c-.357 0-.423.075-.687.33a.56.56 0 0 1-.367.14H9.94a.55.55 0 0 1-.367-.14c-.264-.255-.33-.33-.687-.33a.55.55 0 0 0-.367.141L6.035 6.507a.5.5 0 0 0-.15.348c0 .132.056.254.15.349l.847.884a.53.53 0 0 0 .734 0l2.079-2.06a.54.54 0 0 1 .367-.146h3.876a.53.53 0 0 1 .362.14l2.084 2.07a.53.53 0 0 0 .734 0l.847-.893a.474.474 0 0 0 0-.692z");
}

</style>
