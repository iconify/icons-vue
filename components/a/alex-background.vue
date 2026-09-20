<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG5ayXMdPj)" class="r4i437pya"/><path class="vn2g_1aoc"/></g><defs><linearGradient id="SVG5ayXMdPj" x1="6.571" x2="16.853" y1="6.145" y2="18.43" gradientUnits="userSpaceOnUse"><stop class="l38xg2bdk"/><stop offset="1" class="o0e34db_q"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:alex-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l38xg2bdk {
  stop-color: var(--svg-color--6b2cfe, #6b2cfe);
}

.o0e34db_q {
  stop-color: var(--svg-color--078ce0, #078ce0);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vn2g_1aoc {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.73 17.438a8 8 0 0 1-.7-.94l4.485-4.495L5.02 7.508q.322-.497.705-.94l5.44 5.435zm-1.3-8.846c-.17.39-.315.8-.43 1.21l2.2 2.2L4 14.198c.115.41.26.816.435 1.206l3.41-3.4l-3.41-3.41zm7.57 4.25l-5.435 5.43c.295.26.61.49.94.7L12 14.488l4.5 4.496c.325-.21.64-.45.935-.7L12 12.837zm3.41 6.725L12 16.153l-3.41 3.41c.39.175.8.32 1.21.435l2.2-2.2l2.195 2.2a8 8 0 0 0 1.215-.434zm-3.41-8.4l5.435-5.434a8 8 0 0 0-.94-.7L12 9.517L7.505 5.023q-.496.323-.94.704zm7.565 4.246c.175-.39.32-.796.435-1.206l-2.2-2.204l2.2-2.2a9 9 0 0 0-.435-1.216l-3.415 3.416l3.41 3.41zm-5.085-3.41l4.495-4.495a9 9 0 0 0-.7-.94l-5.44 5.435l5.43 5.435c.26-.3.495-.61.7-.94l-4.48-4.495zM12 7.853l3.41-3.415a8 8 0 0 0-1.21-.435l-2.2 2.2l-2.2-2.2c-.41.114-.815.26-1.205.435l3.4 3.41z");
}

</style>
