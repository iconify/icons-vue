<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="p7c1j7y-w"/><path class="o4thfd00r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ccd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.o4thfd00r {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.35 6.86a5.658 5.658 0 0 0-7.996 5.123c0 3.128 2.573 5.668 5.692 5.668c.823 0 1.6-.183 2.305-.498v2.511a8.048 8.048 0 0 1-10.349-7.681a8.01 8.01 0 0 1 10.349-7.634zm4.94 8.425h-2.705a5.64 5.64 0 0 0 0-6.604h2.7a8 8 0 0 1 0 6.604z");
}

.p7c1j7y-w {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 15.3a3.293 3.293 0 1 0 0-6.586a3.293 3.293 0 0 0 0 6.585");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
