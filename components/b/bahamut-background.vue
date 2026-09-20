<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oiaq0acft"/><path class="nuglnccmt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bahamut-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nuglnccmt {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.492 4.3q-3.503-.6-7.004 0c-1.046.16-2.013.641-2.737 1.442S4.463 7.424 4.3 8.546a20.3 20.3 0 0 0 0 6.968c.162 1.042.645 2.083 1.45 2.804a5.03 5.03 0 0 0 2.818 1.442c1.127.16 2.334.24 3.461.24c1.208 0 2.335-.08 3.462-.32c1.046-.16 2.093-.641 2.817-1.442c.805-.801 1.288-1.762 1.45-2.804c.16-1.121.241-2.323.241-3.444c0-1.201-.08-2.323-.322-3.444c-.161-1.042-.644-2.003-1.45-2.804c-.643-.8-1.61-1.281-2.736-1.442M10.42 17.277a.73.73 0 0 1-.563-.24c-.242-.241-.242-.722-.08-.962l2.012-2.723l-3.301-.32c-.322 0-.644-.241-.724-.642c-.081-.32 0-.72.241-.96l5.072-4.566a.73.73 0 0 1 .563-.24c.242 0 .403.08.564.24a.98.98 0 0 1 .08 1.04l-2.012 2.724l3.3.32c.322 0 .644.241.805.641c.08.32 0 .721-.241.962l-5.072 4.565c-.241.08-.402.16-.644.16");
}

.oiaq0acft {
  fill: var(--svg-color--a60063, #a60063);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
