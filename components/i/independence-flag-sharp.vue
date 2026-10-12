<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t3-oq195p"/><path class="w49dqzbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:independence-flag-sharp" /></template>
<style>
.t3-oq195p {
  d: path("M4 2.75v18.5m0-17C6.75 3 9.35 3 12.1 4.25s5.4 1.25 8.15 0v9.5c-2.75 1.25-5.4 1.25-8.15 0s-5.35-1.25-8.1 0Z");
}

.w49dqzbaa {
  d: path("m8.64 6.12l.41.91l.14.32l.35.03l.99.11l.35.04l-.26.23l-.74.67l-.26.23l.07.35l.21.97l.07.34l-.3-.17l-.87-.5l-.3-.17l-.3.17l-.87.5l-.3.17l.07-.34l.21-.97l.07-.35l-.26-.23l-.74-.67l-.26-.23l.35-.04l.99-.11l.35-.03l.14-.32l.41-.91l.14-.32zM13 7.75l3.625 1.595L20.25 7.75m-7.25 3l3.625 1.595l3.625-1.595");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
