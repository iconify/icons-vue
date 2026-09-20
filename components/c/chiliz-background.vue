<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="szuq8_eqt"/><path class="perzq_e1j"/><path clip-rule="evenodd" class="wwvbygb3o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:chiliz-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.perzq_e1j {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.878 6.366l-2.286 1.41a.096.096 0 0 1-.132-.031l-.135-.217a.593.593 0 0 1 .192-.816l.89-.545a.277.277 0 0 0 .05-.432l-.745-.687a.593.593 0 0 1-.003-.838l.18-.182a.096.096 0 0 1 .136 0l1.91 1.845c.144.144.144.379-.057.493");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.szuq8_eqt {
  fill: var(--svg-color--f60250, #f60250);
  d: path("M24 0H0v24h24z");
}

.wwvbygb3o {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.202 13.062a2.54 2.54 0 0 1 .596 2.28s-.11 1.07-.736 3.553c-.174.69.5 1.3 1.166 1.047c4.534-1.724 4.531-6.328 4.531-6.328c.133-2.965-2.872-5.835-3.736-6.632a.4.4 0 0 0-.484-.043L9.178 8.448a1.98 1.98 0 0 0-.419 2.978zm-.471-3.758l1.658-1.05a.286.286 0 0 1 .348.032c4.648 4.374 2.42 7.673.83 9.045c-.374.323-.943-.014-.833-.496l.253-1.11a3.92 3.92 0 0 0-.918-3.517L9.56 10.464a.774.774 0 0 1 .171-1.16");
}

</style>
