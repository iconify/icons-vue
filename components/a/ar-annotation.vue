<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlltjpk9b"/><path class="rvouiy02z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ar-annotation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nlltjpk9b {
  d: path("M12.164 21.223q-.27.025-.536-.033q-.265-.057-.501-.193l-6.5-3.742q-.1-.057-.191-.127t-.172-.151q-.082-.081-.152-.172t-.127-.191t-.102-.205t-.073-.217q-.03-.111-.045-.225t-.015-.229V8.262q0-.115.015-.229t.045-.225t.073-.217t.102-.205q.057-.1.127-.191t.152-.172t.172-.151q.091-.07.191-.127l6.5-3.742q.099-.057.205-.101q.106-.043.216-.073q.111-.03.224-.044q.114-.015.228-.015t.228.015q.113.014.224.044q.11.03.216.073q.106.044.205.101l6.5 3.742q.1.057.191.127t.172.151t.152.172t.127.191q.058.099.102.205t.073.217q.03.111.045.225t.015.229v4.348");
}

.rvouiy02z {
  d: path("M3.75 7.25L12 12l8.25-4.75M12 12v7m0 1v1.5m2.75-1.625v-.754a1.5 1.5 0 0 1 .439-1.06l2.5-2.5a1.5 1.5 0 0 1 2.122 0l.628.628a1.5 1.5 0 0 1 0 2.122l-2.5 2.5a1.5 1.5 0 0 1-1.06.439h-.754a1.375 1.375 0 0 1-1.375-1.375");
}

</style>
