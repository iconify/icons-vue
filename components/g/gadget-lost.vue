<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejgxwsb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gadget-lost" /></template>
<style>
.ejgxwsb8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.464 17.75l-1.383.294q-.168.036-.339.055t-.343.021t-.343-.012t-.34-.046t-.335-.079t-.325-.112t-.312-.143t-.297-.172t-.278-.201t-.258-.228t-.234-.251q-.111-.132-.208-.273t-.18-.293q-.083-.15-.151-.308t-.12-.322t-.088-.332L5.267 7.523q-.036-.168-.055-.339t-.021-.343t.012-.343q.015-.171.046-.34q.032-.17.079-.335q.048-.165.112-.325q.064-.159.143-.312t.172-.297q.094-.144.201-.278t.228-.258t.251-.234q.132-.111.273-.208t.293-.18q.15-.083.308-.151t.322-.12t.332-.088l1.956-.416q.168-.036.339-.055t.343-.021t.343.012q.171.015.34.046q.17.032.335.079q.165.048.325.112q.159.064.312.143t.297.172t.278.201q.135.108.258.228t.234.251t.208.273t.18.293q.083.15.151.308t.12.322t.088.332l1.526 7.182M8.238 5.869l2.445-.52M15.25 17.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
