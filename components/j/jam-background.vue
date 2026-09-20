<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ek7klttre"/><path class="hzecc8b-o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:jam-background" /></template>
<style>
.ek7klttre {
  fill: var(--svg-color--eb2324, #eb2324);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hzecc8b-o {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.108 4C16.25 4 20 7.835 20 11.943C20 18.132 15.115 20 14.07 20c-1.373 0-1.6-1.718-1.6-2.424c0-.705 1.728-3.223 3.568-3.223c.8 0 .842.259 1.139.47c.334-.46.46-1.223.47-2.094c.042-3.091-2.776-4.884-5.553-4.964h-.188c-2.748 0-5.581 1.995-5.553 4.964c.01 1.05.24 1.963.48 2.095c.282-.198.315-.471 1.13-.471c1.84 0 3.566 2.518 3.566 3.223S11.303 20 9.93 20C8.885 20 4 18.132 4 11.943C4 7.85 7.746 4 11.878 4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
