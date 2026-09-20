<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nufz_bbgu"/><path class="paso4uhin"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gleec-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nufz_bbgu {
  fill: var(--svg-color--843af9, #843af9);
  d: path("M24 0H0v24h24z");
}

.paso4uhin {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.737 4h2.526v2.105c1.895 0 4.004 1.185 4.504 3.369H15.47c-.438-1.117-1.448-1.263-2.684-1.263l-1.573-.01c-1.627 0-3.003.973-3.003 2.656v2.286c0 1.683 1.425 2.646 3.053 2.646h1.474c1.628 0 2.947-1.264 2.947-2.947h-6.21v-2.105h8.42v2.406c0 2.735-2.21 4.752-4.63 4.752V20h-2.527v-2.105c-2.526 0-4.632-2.017-4.632-4.752v-2.286c0-2.735 2.106-4.752 4.632-4.752z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
