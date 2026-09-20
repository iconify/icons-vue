<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dblrqk6lg"/><path class="wkqocsc2i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:creo-background" /></template>
<style>
.dblrqk6lg {
  fill: var(--svg-color--39b0f4, #39b0f4);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wkqocsc2i {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.222 4v2.169L7.595 8.925a.5.5 0 0 0-.262.43v5.268c0 .178.053.285.205.378l4.564 2.716a.49.49 0 0 0 .502 0l4.045-2.467l1.796 1.342l-5.587 3.276a.99.99 0 0 1-1.005-.01l-5.809-3.524a1.02 1.02 0 0 1-.489-.867v-7c0-.36.187-.693.49-.876zm0 2.596V8.12l-2.978 1.8c-.097.063-.133.218-.133.334v3.458l-.004.084c-.01.085-.014.156.062.2l2.898 1.743a.32.32 0 0 0 .329 0l2.649-1.618l1.169.875l-3.654 2.147a.64.64 0 0 1-.653-.004l-3.8-2.312a.68.68 0 0 1-.33-.569V9.677c0-.236.134-.453.33-.578L12.221 6.6zm.223 7.182a1.555 1.555 0 1 0 0-3.11a1.555 1.555 0 0 0 0 3.11m4.889-4.333a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-2.445 1.222a.444.444 0 1 0 0-.888a.444.444 0 0 0 0 .888");
}

</style>
