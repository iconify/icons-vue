<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="mfnn8_zji"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctg-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mfnn8_zji {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-1.882 0a6.118 6.118 0 1 1-12.235 0a6.118 6.118 0 0 1 12.235 0m-10.824-.235c.08-1.487 1.144-4.47 4.73-4.47a4.7 4.7 0 0 1 4.211 2.64h-1.727c-.155-.246-.602-.744-1.106-.744c-.63 0-1.185.734-1.378 1.247l-.043.103a8.4 8.4 0 0 0-.588 3.308c0 1.897 1.572 3.205 2.955 1.403c-.583-.094-1.755-.504-1.755-1.403c-.047-.226.198-.677 1.534-.677c1.666 0 1.986.555 1.986 1.007s-.72 2.527-3.52 2.527c-2.805 0-3.27-2.433-3.27-3.826c0-1.12.733-2.701 1.1-3.355c.034-.066.048-.18-.16-.1c-.258.095-1.962 1.333-1.962 3.286a3.3 3.3 0 0 0-1.007-.942z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
