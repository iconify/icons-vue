<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="oy4-oec3z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:htr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.oy4-oec3z {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.889 12c0-3.898 3.213-7.111 7.111-7.111S19.111 8.102 19.111 12S15.898 19.111 12 19.111S4.889 15.898 4.889 12M12 4a8 8 0 1 0 0 16a8 8 0 0 0 0-16m1.333 5.778c-1.129.04-2.088.382-2.666 1.333V6.667H9.333v6.666h-.889v1.334H12v-1.334h-.889v-.604c0-.844.84-1.778 1.707-1.8c1.178-.031 1.755.72 1.849 1.8v4.16H16v-4.622c0-1.6-1.333-2.49-2.667-2.49m-4.889 5.778v1.333H12v-1.333z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
