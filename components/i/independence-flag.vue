<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t3-oq195p"/><path class="ev0i51b4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:independence-flag" /></template>
<style>
.ev0i51b4g {
  d: path("m8.64 6.12l.41.91q.14.32.49.35l.99.11q.35.04.09.27l-.74.67q-.26.23-.19.58l.21.97q.07.34-.23.17l-.87-.5q-.3-.17-.6 0l-.87.5q-.3.17-.23-.17l.21-.97q.07-.35-.19-.58l-.74-.67q-.26-.23.09-.27l.99-.11q.35-.03.49-.35l.41-.91q.14-.32.28 0M13 7.75c2.5 1.1 4.75 1.1 7.25 0m-7.25 3c2.5 1.1 4.75 1.1 7.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t3-oq195p {
  d: path("M4 2.75v18.5m0-17C6.75 3 9.35 3 12.1 4.25s5.4 1.25 8.15 0v9.5c-2.75 1.25-5.4 1.25-8.15 0s-5.35-1.25-8.1 0Z");
}

</style>
