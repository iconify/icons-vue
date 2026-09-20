<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q_eq88bqj"/><path class="f-5b686kt"/><path class="izk_gg_wj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:etn-background" /></template>
<style>
.f-5b686kt {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.438 16.77a7.31 7.31 0 0 1 9.544-10.905l.653-.336A7.963 7.963 0 0 0 5.991 17.244zm1.37-3.633l1.318 1.002L6.95 16.44a6.7 6.7 0 0 1 8.534-10.164L9.207 9.51l-.97.498l.902.623l.64.447l-1.872.952l-.934.48zm7.204-2.805l2.345-2.476a6.7 6.7 0 0 1-8.38 10.165l5.954-3.067l.97-.498l-.896-.622l-.647-.447l1.873-.959l.933-.472zm2.65-2.974a7.31 7.31 0 0 1-9.407 10.925l-.672.341A7.963 7.963 0 0 0 18.116 6.88z");
}

.ft5dv1b6b {
  fill: none;
}

.izk_gg_wj {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.249 12.652l1.904 1.437l-4.3 4.536l8.549-4.417l-1.543-1.064l2.849-1.456l-1.903-1.443l4.298-4.53l-8.547 4.418l1.543 1.064z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q_eq88bqj {
  fill: var(--svg-color--091b26, #091b26);
  d: path("M24 0H0v24h24z");
}

</style>
