<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dz1ixyc_x"/><path class="x01bjsbbe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hopr-background" /></template>
<style>
.dz1ixyc_x {
  fill: var(--svg-color--ffff9f, #ffff9f);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x01bjsbbe {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.422 20c.154-4.594.067-11.871-.357-16h2.68l.35 6.369c.785-1.146 2.736-3.02 4.852-2.56c2.11.465 2.684 1.548 3.489 3.943c.686 2.05.516 6.178.35 8.248h-2.688c.707-6.978-.444-10.957-2.85-9.068C9.592 13.017 9.209 17.322 9.1 20H6.416z");
}

</style>
