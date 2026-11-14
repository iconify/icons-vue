<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sshc9bcsx"/><path class="bu_ycwh0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:box-cutter" /></template>
<style>
.bu_ycwh0w {
  d: path("m15.887 9.521l2.767-1.007a1.06 1.06 0 0 1 1.355 1.369l-.568 1.512a1.5 1.5 0 0 1-.891.882l-1.466.533a1.5 1.5 0 0 1-1.923-.896l-.171-.47a1.5 1.5 0 0 1 .897-1.923m-9.078.644l1.88-.684a.75.75 0 0 1 .961.448a.75.75 0 0 1-.448.961l-1.88.684a.75.75 0 0 1-.961-.448a.75.75 0 0 1 .448-.961m10.252-1.071l.023 3.716");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sshc9bcsx {
  d: path("m4.033 12.771l8.458-3.078a1.75 1.75 0 0 1 2.243 1.046l.684 1.879a1.75 1.75 0 0 1-1.046 2.243l-8.011 2.916a1.75 1.75 0 0 1-1.338-.058l-.609-.284a1.75 1.75 0 0 1-.905-.988l-.522-1.433a1.75 1.75 0 0 1 1.046-2.243");
}

</style>
