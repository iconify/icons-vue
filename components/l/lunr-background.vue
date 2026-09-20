<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGJMrhRbKl)" class="h4gmohbze"/></g><defs><linearGradient id="SVGJMrhRbKl" x1="10.444" x2="10.444" y1="7.848" y2="10.469" gradientUnits="userSpaceOnUse"><stop class="vzflefbnw"/><stop offset="1" class="hfcbrhxzx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lunr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h4gmohbze {
  d: path("M19.21 16.234a.137.137 0 0 1-.132-.17c.14-.545.216-1.12.216-1.713c0-3.896-3.266-7.058-7.294-7.058s-7.294 3.162-7.294 7.059c0 .592.075 1.167.216 1.712a.137.137 0 0 1-.131.17a.13.13 0 0 1-.118-.08a8.001 8.001 0 1 1 14.654 0a.13.13 0 0 1-.118.08M12 19.057a4.235 4.235 0 1 0 0-8.47a4.235 4.235 0 0 0 0 8.47");
}

.hfcbrhxzx {
  stop-color: var(--svg-color--21fa90, #21fa90);
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vzflefbnw {
  stop-color: var(--svg-color--07edfd, #07edfd);
}

</style>
