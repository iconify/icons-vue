<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm8lo6v1l"/><path class="l_xbp3b4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guard-badge" /></template>
<style>
.cm8lo6v1l {
  d: path("m12 2.75l6.6 2.45a1 1 0 0 1 .65.94v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14a1 1 0 0 1 .65-.94Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_xbp3b4b {
  d: path("m12.14 7.57l.89 1.99q.15.32.49.36l2.17.23q.35.04.09.27l-1.62 1.46q-.26.24-.19.58l.46 2.14q.07.34-.24.16l-1.89-1.09q-.3-.17-.6 0l-1.89 1.09q-.31.18-.24-.16l.46-2.14q.07-.34-.19-.58l-1.62-1.46q-.26-.23.09-.27l2.17-.23q.34-.04.49-.36l.89-1.99q.14-.32.28 0");
}

</style>
