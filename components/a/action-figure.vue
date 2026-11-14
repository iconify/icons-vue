<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-12ddczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:action-figure" /></template>
<style>
.z-12ddczd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.5q-2.75 0-2.75 2.75T12 7t2.75-2.75T12 1.5M4.431 12.012l3-3.5q.106-.125.256-.193q.149-.069.313-.069h8q.164 0 .313.069q.15.068.256.193l3 3.5q.098.113.144.255t.035.291q-.012.148-.079.281q-.068.133-.181.23q-.056.049-.12.085q-.065.036-.135.059t-.144.032q-.073.008-.147.003q-.073-.006-.144-.026t-.137-.053t-.124-.079t-.106-.102L15.655 9.75h-.405v4.176l.865 4.324h1.135q2 0 2 2t-2 2H6.75q-2 0-2-2t2-2h1.135l.865-4.324V9.75h-.405l-2.776 3.238q-.097.113-.23.181t-.281.079t-.291-.035t-.255-.144q-.113-.097-.181-.23t-.079-.281t.035-.291q.046-.142.144-.255m9.334 2.135l.82 4.103h-5.17l.82-4.103q.015-.073.015-.147V9.75h3.5V14q0 .074.015.147");
}

</style>
