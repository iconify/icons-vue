<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yd0c_zbka"/><path class="qfxspobmg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:idrt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qfxspobmg {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.792 6.484a8 8 0 0 1 1.67 2.639v.007a8 8 0 0 1 .529 3.26a7.993 7.993 0 0 1-8.603 7.584a8 8 0 0 1-3.376-1.044a7.8 7.8 0 0 1-1.673-1.27A8 8 0 0 1 9.113 4.544a7.99 7.99 0 0 1 8.679 1.94M9.17 7.503H6.5v7.5h1v-3h1.67l1.77 3h1.355l-1.962-3.261c1.02-.09 1.414-1.172 1.414-2.12c0-1.092-.47-1.83-1.503-2.017a5.6 5.6 0 0 0-1.074-.102m1.448 2.24c0 1.036-.973 1.26-1.68 1.26H7.5v-2.5h1.557c.647.003 1.56.343 1.56 1.24m2.882-.24h-1v7.5h1v-3.054c.42.522 1.27.79 1.929.782c1.437.013 2.585-1.221 2.57-2.641c.018-1.442-1.075-2.662-2.57-2.637c-.694-.01-1.564.255-1.93.877zm1.83 1c.741 0 1.67.456 1.67 1.587c0 .935-.522 1.645-1.571 1.66c-1.05.015-1.506-.604-1.686-1.09c-.375-1.01.413-2.157 1.587-2.157");
}

.yd0c_zbka {
  fill: var(--svg-color--bb4e42, #bb4e42);
  d: path("M24 0H0v24h24z");
}

</style>
