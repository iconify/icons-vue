<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vkjfl93el"/><path class="swyqah7mw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:catamaran" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.swyqah7mw {
  d: path("M12 5.5v6q0 1-1 1H6.5q-1 0-.37-.78l5.24-6.44q.63-.78.63.22m0 7v3m-9.25 0h18.5m-17.5 0h3.5v2.75a1.75 1.75 0 0 1-3.5 0Zm13 0h3.5v2.75a1.75 1.75 0 0 1-3.5 0Z");
}

.vkjfl93el {
  d: path("M12 3.75v7.75q0 1 1 1h5.5q1 0 .39-.79l-6.28-8.17q-.61-.79-.61.21");
}

</style>
