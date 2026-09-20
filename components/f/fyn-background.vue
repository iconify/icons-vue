<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q1mlk3b2i"/><path class="r27e4-tjw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fyn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q1mlk3b2i {
  fill: var(--svg-color--ff5757, #ff5757);
  d: path("M24 0H0v24h24z");
}

.r27e4-tjw {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.72 19.529c2.113 0 4.4-2.01 5.28-3.012c-.96.283-3.115.862-4.268.862c-1.44 0-4.96-1.615-6.4-1.615s-2.531.753-3.251.537c-.72-.212 4.851-9.68 5.388-9.68c.532 0 2.531 4.518 3.731 6.24s1.2 2.15.96 2.15s-1.2-.216-1.68-.644c-.48-.433-2.4-4.09-3.12-4.09c-.578 0-2.164 3.3-2.88 4.951C9.28 14.15 10.976 12 11.36 12c.48 0 1.44 2.367 1.92 3.44c.48 1.077 3.12 1.077 4.32.86c1.2-.21.48-1.505 0-2.15c-.48-.644-3.84-6.667-4.32-7.529c-.48-.86-.611-2.15-1.811-2.15S7.28 8.77 6.32 10.922c-.96 2.156-2.88 6.885-2.165 7.53c.725.649 1.633-.537 3.313-.537s4.611 1.614 7.247 1.614z");
}

</style>
