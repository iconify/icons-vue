<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="pitnx1z0t"/><path class="oums96r2y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:grnd-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.oums96r2y {
  fill: var(--svg-color--fe3000, #fe3000);
  d: path("M18.592 6.821h-7.767L7.671 8.676l-.837 2.88l1.675 1.384h3.573l-.212.942H8.51l-3.15 1.59l-.419 1.234h7.767l3.154-1.647l1.05-3.088l-1.888-1.384H11.45l.424-.941h3.356l2.942-1.591z");
}

.pitnx1z0t {
  fill: var(--svg-color--000, #000);
  d: path("M4.852 18.12c-.513 0-.353-.424-.212-.632H4l.852-2.532l2.768-1.478l-1.502-1.304a.42.42 0 0 1-.132-.428l.951-3.385a.42.42 0 0 1 .188-.244l3.587-2.175a.45.45 0 0 1 .221-.061h8.196a.423.423 0 0 1 .395.579l-.189.475h.24a.423.423 0 0 1 .4.565l-.64 1.756l-2.772 1.478l.852.635s.64.424.424.631c.518.17.503.494.428.63l-1.224 3.437a.42.42 0 0 1-.197.23l-3.385 1.775a.4.4 0 0 1-.202.047z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
