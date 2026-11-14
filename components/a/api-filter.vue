<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fdzkfebtv"/><path class="mpdskubyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api-filter" /></template>
<style>
.fdzkfebtv {
  d: path("m12.167 15.673l-2.292 1.322q-.099.057-.205.101t-.217.074t-.225.044q-.113.015-.228.015t-.228-.015q-.114-.014-.225-.044t-.217-.074t-.205-.101l-4.75-2.74q-.099-.057-.19-.127t-.173-.151q-.081-.081-.15-.172q-.07-.091-.128-.191q-.057-.099-.101-.205t-.073-.217t-.045-.225t-.015-.228V7.261q0-.115.015-.228q.015-.114.045-.225t.073-.217t.101-.205t.128-.191q.069-.091.15-.172q.082-.081.173-.151t.19-.127l4.75-2.74q.099-.057.205-.101t.217-.074t.225-.044T9 2.771t.228.015q.114.014.225.044t.217.074t.205.101l4.75 2.74q.099.057.19.127t.173.151q.081.081.15.172q.07.091.128.191q.057.099.101.205t.073.217t.045.225t.015.228v2.966");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpdskubyp {
  d: path("M2.5 6.25L9 10l6.5-3.75M9 10v7.5m6.901-4.5h3.198A1.154 1.154 0 0 1 20 14.875l-1.117 1.396a1.75 1.75 0 0 0-.383 1.093v3.018a.69.69 0 0 1-1 .618l-.033-.016a1.75 1.75 0 0 1-.967-1.566v-2.054a1.75 1.75 0 0 0-.383-1.093L15 14.875A1.154 1.154 0 0 1 15.901 13");
}

</style>
