<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e8bwzabyx"/><path class="vh624wb2o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ftn-background" /></template>
<style>
.e8bwzabyx {
  fill: var(--svg-color--ff008c, #ff008c);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vh624wb2o {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.326 19.974a1.23 1.23 0 0 0 1.063-.282l7.757-6.867a1.35 1.35 0 0 0 .377-1.421a1.35 1.35 0 0 0-1.168-.918l-4.984-.471l3.045-4.132a1.195 1.195 0 0 0-.122-1.535A1.25 1.25 0 0 0 14.442 4c-.301 0-.593.108-.814.31l-7.766 6.853a1.338 1.338 0 0 0 .07 2.062c.207.165.462.259.725.282l4.984.48l-3.045 4.133a1.177 1.177 0 0 0 .73 1.854");
}

</style>
