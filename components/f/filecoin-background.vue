<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vj80-ofis"/><path class="xvpzaeapv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:filecoin-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vj80-ofis {
  fill: var(--svg-color--0090ff, #0090ff);
  d: path("M24 0H0v24h24z");
}

.xvpzaeapv {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.077 10.628l-.369 1.875l3.508.47l-.246.878l-3.446-.47c-.246.764-.37 1.584-.677 2.287c-.308.82-.616 1.64-.985 2.404c-.493.996-1.354 1.7-2.523 1.874c-.677.118-1.415.059-1.97-.35c-.183-.117-.369-.352-.369-.528c0-.235-.005-.51.308-.645s.441-.04.616.058c.184.176.369.41.492.645c.369.47.861.528 1.354.175c.554-.467.862-1.113 1.046-1.757c.369-1.407.739-2.755 1.045-4.161v-.236l-3.26-.469l.122-.878l3.386.469l.43-1.817l-3.508-.528l.124-.937l3.63.469c.123-.353.185-.645.309-.938c.306-1.056.614-2.11 1.353-3.049c.738-.938 1.6-1.523 2.892-1.465c.554 0 1.108.176 1.477.587c.062.058.184.175.184.291c0 .236 0 .529-.184.705c-.246.175-.554.117-.8-.117c-.185-.176-.308-.352-.493-.528c-.368-.469-.922-.527-1.353-.117a3.7 3.7 0 0 0-.8 1.113c-.432 1.231-.739 2.52-1.17 3.81l3.385.47l-.246.878z");
}

</style>
