<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3lnujpgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:black-flag" /></template>
<style>
.h3lnujpgh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 1.75h5.5q2.5 0 2.5 2.5v7.5q0 2.5-2.5 2.5h-2v3.905l3.238 2.776q.113.097.181.23t.079.281q.011.149-.035.291t-.144.255t-.23.181t-.281.079t-.291-.035t-.255-.144L12 19.488l-3.012 2.581q-.113.098-.255.144t-.291.035q-.148-.012-.281-.079q-.133-.068-.23-.181q-.049-.056-.085-.12q-.036-.065-.059-.135t-.032-.144t-.003-.147t.026-.144t.053-.137t.079-.124t.102-.106l3.238-2.776V14.25h-2q-2.5 0-2.5-2.5v-7.5q0-2.5 2.5-2.5");
}

</style>
