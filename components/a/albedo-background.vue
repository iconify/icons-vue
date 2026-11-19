<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="ql3n-bbuh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:albedo-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ql3n-bbuh {
  fill: var(--svg-color--0691b7, #0691b7);
  d: path("M12.334 4h-.668L4.9 19.991l.02.009h1.806l1.354-3.2a13.36 13.36 0 0 0 8.666-.045L18.119 20h.96l.02-.009Zm.014 12.895c-1.37 0-2.732-.221-4.031-.655l4.105-9.704l4.088 9.661a12.8 12.8 0 0 1-4.162.698");
}

</style>
