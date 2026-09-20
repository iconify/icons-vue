<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c9q-3-9tz"/><path clip-rule="evenodd" class="w3a9oobxd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aleph-background" /></template>
<style>
.c9q-3-9tz {
  fill: var(--svg-color--0055fe, #0055fe);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w3a9oobxd {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.307 16.913A7.994 7.994 0 0 0 6.567 6.137l.674.674a.666.666 0 1 1-.94.944l-.634-.634a7.993 7.993 0 0 0 4.661 12.704a.7.7 0 0 1 .2-.355l2.114-2.118a.75.75 0 1 1 1.059 1.06L12.11 20a7.96 7.96 0 0 0 5.291-2.108l-.549-.55a.666.666 0 0 1 .722-1.093a.7.7 0 0 1 .217.144zM9.994 9.259a1.25 1.25 0 1 1-2.498 0a1.25 1.25 0 0 1 2.498 0m.694-2.608a.664.664 0 1 0 .94.94l1.883-1.884a.666.666 0 0 0-.206-1.1a.66.66 0 0 0-.733.16zm-.055 4.047a.665.665 0 0 1 .94 0l1.888 1.888a.667.667 0 0 1-.944.94l-1.884-1.884a.665.665 0 0 1 0-.94zm5.855 4.556a1.249 1.249 0 1 1-2.498 0a1.249 1.249 0 0 1 2.498 0");
}

</style>
