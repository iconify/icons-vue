<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ryho19blh"/><path class="c2s69ub1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-restricted" /></template>
<style>
.c2s69ub1p {
  d: path("M2.5 5.75L9 9.5l6.5-3.75M9 9.5v6.75M5.75 3.75l6.5 3.75m.75 10a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m2.25 0h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ryho19blh {
  d: path("m10.478 15.397l-.603.348q-.099.057-.205.101t-.217.074t-.225.044t-.228.015t-.228-.015q-.114-.014-.225-.044t-.217-.074t-.205-.101l-4.75-2.74q-.099-.057-.19-.127t-.173-.151q-.081-.081-.15-.172q-.07-.091-.128-.191q-.057-.099-.101-.205t-.073-.217t-.045-.225t-.015-.228V6.761q0-.115.015-.228q.015-.114.045-.225t.073-.217t.101-.205t.128-.191q.069-.091.15-.172q.082-.081.173-.151t.19-.127l4.75-2.74q.099-.057.205-.101t.217-.074t.225-.044T9 2.271t.228.015q.114.014.225.044t.217.074t.205.101l4.75 2.74q.099.057.19.127t.173.151q.081.081.15.172q.07.091.128.191q.057.099.101.205t.073.217t.045.225t.015.228v3.666");
}

</style>
