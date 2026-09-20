<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vj80-ofis"/><path class="k_tkix-4z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fil-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k_tkix-4z {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.077 10.627l-.37 1.875l3.508.47l-.246.879l-3.446-.47c-.246.763-.369 1.583-.677 2.287c-.307.82-.615 1.64-.985 2.403c-.492.996-1.354 1.7-2.523 1.875c-.677.118-1.415.06-1.969-.351c-.184-.117-.369-.352-.369-.528c0-.234-.005-.51.308-.645c.312-.134.441-.04.615.06c.185.175.37.41.492.645c.37.468.862.526 1.354.174c.554-.468.862-1.112 1.047-1.758c.368-1.406.738-2.754 1.045-4.161v-.235L7.6 12.678l.123-.879l3.385.47l.43-1.818l-3.508-.527l.124-.938l3.63.469c.123-.352.185-.645.308-.938c.308-1.055.615-2.11 1.354-3.047s1.6-1.524 2.893-1.466c.553 0 1.107.176 1.476.586c.062.059.185.176.185.293c0 .235 0 .528-.185.704c-.246.176-.553.117-.8-.117c-.185-.176-.308-.353-.492-.528c-.369-.469-.923-.527-1.354-.117a3.7 3.7 0 0 0-.8 1.114c-.43 1.23-.738 2.52-1.169 3.81l3.385.468l-.247.879z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vj80-ofis {
  fill: var(--svg-color--0090ff, #0090ff);
  d: path("M24 0H0v24h24z");
}

</style>
