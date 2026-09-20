<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="scueclw5o"/><path class="nzvj4cbzw"/><path class="dsn9wlbzu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:agix-background" /></template>
<style>
.dsn9wlbzu {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.667 7.687c0-1.449-1.147-2.69-1.805-3.227c-.098-.08-.124-.222-.044-.32a.25.25 0 0 1 .31-.067c1.023.56 2.77 1.992 2.77 3.916c0 1.134-.489 2.054-1.147 2.788c-.213.124-.458.164-.71.022c-.485-.271-.25-.827-.014-1.258a3.1 3.1 0 0 0 .64-1.858zm-4.712 6.819h.027a3.1 3.1 0 0 0-.65 1.765c0 1.351 1.125 2.72 1.81 3.342c.093.09.102.232.009.316a.25.25 0 0 1-.294.031l-.013-.004c-.711-.4-2.738-1.534-2.738-3.97c0-1 .427-1.84.987-2.52c.266-.231.578-.382.862-.222c.534.306.218.95 0 1.258z");
}

.ft5dv1b6b {
  fill: none;
}

.nzvj4cbzw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.164 4.505c-.67.56-1.831 1.827-1.831 3.254c0 1.774 2.125 2.978 3.232 3.623l.355.213c.925.57 3.08 1.992 3.08 4.268c0 2.16-1.866 3.587-2.853 4.111a.24.24 0 0 1-.276-.04a.22.22 0 0 1-.047-.256a.2.2 0 0 1 .056-.073c.711-.622 1.787-1.964 1.787-3.311c0-1.854-1.591-2.845-2.822-3.556l-.147-.09c-1.534-.884-3.699-2.133-3.699-4.609c0-1.898 1.805-3.414 2.845-4a.295.295 0 0 1 .383.08a.283.283 0 0 1-.063.386");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.scueclw5o {
  fill: var(--svg-color--311879, #311879);
  d: path("M24 0H0v24h24z");
}

</style>
