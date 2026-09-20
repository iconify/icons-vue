<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w3pampbye"/><path class="x7y45j9yv"/><path class="a8hom_qba"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dusk-background" /></template>
<style>
.a8hom_qba {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.697 10.002h-9.93c-.075 0-.25.185-.265.47c-.01.284.16.53.265.53h9.93c.11 0 .3-.216.3-.53s-.17-.47-.3-.47m0 2.998h-9.93c-.075 0-.25.185-.265.47c-.01.285.16.53.265.53h9.93c.11 0 .3-.215.3-.53s-.17-.47-.3-.47");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w3pampbye {
  fill: var(--svg-color--523b97, #523b97);
  d: path("M24 0H0v24h24z");
}

.x7y45j9yv {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.058 4.044a8.96 8.96 0 0 1 6.927 2.299a7.61 7.61 0 0 1 0 11.31a8.95 8.95 0 0 1-6.927 2.303a.06.06 0 0 1-.055-.055c0-.03.025-.055.055-.06c1.949-.18 3.998-.974 5.377-2.258C13.035 16.093 14 14.099 14 12s-.965-4.078-2.564-5.567c-1.379-1.284-3.433-2.1-5.377-2.279a.05.05 0 0 1-.055-.05c0-.03.025-.06.055-.06");
}

</style>
