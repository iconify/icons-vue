<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oph9_3bjq"/><path class="wl_8e5y6g"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cream-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oph9_3bjq {
  fill: var(--svg-color--69e2db, #69e2db);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wl_8e5y6g {
  fill: var(--svg-color--000, #000);
  d: path("m13.97 12.595l4.453 4.428a.845.845 0 0 1-.09 1.265a8.06 8.06 0 0 1-9.457.343A7.979 7.979 0 0 1 9.883 4.79a8.07 8.07 0 0 1 8.48.94a.837.837 0 0 1 .055 1.241l-4.453 4.433a.84.84 0 0 0-.25.61c0 .115.025.23.07.335c.045.1.105.2.185.275z");
}

</style>
