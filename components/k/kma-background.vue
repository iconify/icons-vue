<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfNAdCdPs)" class="r4i437pya"/><path clip-rule="evenodd" class="f1zhg0bcf"/></g><defs><linearGradient id="SVGfNAdCdPs" x1="12.749" x2="12.249" y1="3.248" y2="20.008" gradientUnits="userSpaceOnUse"><stop class="aw298xfqg"/><stop offset=".44" class="bc_mz_03x"/><stop offset=".91" class="spdzuzbte"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kma-background" /></template>
<style>
.aw298xfqg {
  stop-color: var(--svg-color--f8a322, #f8a322);
}

.bc_mz_03x {
  stop-color: var(--svg-color--ae5172, #ae5172);
}

.f1zhg0bcf {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.245 5.5c-.07 1.876-.165 2.476-.3 3.336c-.06.37-.125.79-.2 1.381c0 3.292 3.282 3.287 4.223 3.287h.05c.495 0 .73.37.73.75c0 .321-.2.751-.575.751c-5.464 0-5.929-3.837-5.929-5.093c0-.42.1-1.06.2-1.75c.08-.481.155-.992.21-1.472c.11-.79.1-1.496.1-1.866v-.13c0-.565.23-.72.61-.69c.476.01.601.01.866.005l.976-.005h3.317c4.663 0 4.718 3.997 4.718 6.248c0 .46-.28.736-.74.736c-.741 0-.751-.87-.751-1.611c0-3.432-1.671-3.803-3.637-3.878zm6.504 4.252c0-.41-.34-.75-.75-.75s-.75.34-.75.75s.34.75.75.75s.75-.34.75-.75m-3.252 1.25c.41 0 .75.341.75.751s-.34.75-.75.75a.75.75 0 0 1 0-1.5m8.756-3.001a1.501 1.501 0 0 1 .455 2.932c-.165.93-.906 3.557-3.962 3.572H14s.075 3.977-3.827 4.463a1.502 1.502 0 0 1-2.927-.46c.025-.841.685-1.501 1.5-1.501c.531 0 1.002.28 1.272.7c.47-.07 2.731-.586 2.731-4.028v-.235c.015-.35.24-.44.45-.44c.16 0 .316.05.356.07c0 0 2.982 1.2 3.917-2.291A1.5 1.5 0 0 1 18.252 8m0 1a.5.5 0 1 1 0 1a.5.5 0 0 1 0-1m-9.006 9.506a.5.5 0 0 0-.5-.5c-.275 0-.475.2-.5.5a.5.5 0 1 0 1 0");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.spdzuzbte {
  stop-color: var(--svg-color--6804be, #6804be);
}

</style>
