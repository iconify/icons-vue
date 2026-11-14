<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqfofm21u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:handshake-plus" /></template>
<style>
.aqfofm21u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5H6v7H2.5m19-7H18v7h3.5m-6.288.859L13.5 13.5q-.073.029-.149.05t-.154.035t-.157.018t-.157.001t-.157-.015t-.155-.031t-.15-.048q-.074-.027-.145-.063q-.07-.035-.137-.078q-.066-.042-.128-.091q-.062-.05-.118-.105q-.056-.056-.106-.117t-.093-.127q-.044-.065-.08-.136q-.036-.07-.065-.143q-.028-.074-.049-.15L6 10V6l4.5-2h3L18 6v4.5l-2.622 1.748M10 7.75L13.5 10m4.5 5v6m-3-3h6");
}

</style>
