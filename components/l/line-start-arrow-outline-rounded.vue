<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar3tmwbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-arrow-outline-rounded" /></template>
<style>
.ar3tmwbsw {
  fill: currentColor;
  d: path("m10.571 16.044l-5.284-3.367q-.38-.238-.38-.675t.38-.679l5.284-3.367q.404-.268.82-.032q.417.236.417.728V11.5h8.615q.213 0 .356.144t.144.357t-.144.356t-.356.143h-8.615v2.848q0 .492-.417.728q-.416.235-.82-.032m.237-1.04V8.996L6.09 12zm0-3.004");
}

</style>
