<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tfjz8ubcm"/><path class="cg3xbqbdx"/><path class="tyu-aq7jq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gymnet-background" /></template>
<style>
.cg3xbqbdx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 11.5a2 2 0 1 0 0-4a2 2 0 0 0 0 4M19.24 4c-.24 4.03-4.09 7.405-5.98 8.595a7.83 7.83 0 0 0 6.575-1.485c.48-3.08-.2-6.025-.6-7.11z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tfjz8ubcm {
  fill: var(--svg-color--2f6eb6, #2f6eb6);
  d: path("M24 0H0v24h24z");
}

.tyu-aq7jq {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.24 12.595C9.675 16.145 5.69 8.345 4.89 4c-3.284 9.78 3.29 14.52 7.175 16c4.3-1.66 6.575-5.63 7.175-7.405");
}

</style>
