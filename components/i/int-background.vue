<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gtklaqbnc"/><path clip-rule="evenodd" class="piwaqvpib"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:int-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gtklaqbnc {
  fill: var(--svg-color--da1b28, #da1b28);
  d: path("M24 0H0v24h24z");
}

.piwaqvpib {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4L7.5 6.225L12 8.5l4.5-2.275zM9.5 7.825v4.81L8 14.07l1.5 1.415V20h5v-4.515L16 14.07l-1.5-1.215v-5.03l-2.5 2.45zM14 15.92v3.62h-4zm0-6.86l-5.2 4.975h-.005l.475.535v-.36l.73-.625v5.265l5.225-4.815l-.53-.525v.395l-.695.6zm-4 .035v3.125l1.505-1.465zm2-4.605L8.49 6.22L12 7.99l3.515-1.77z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
