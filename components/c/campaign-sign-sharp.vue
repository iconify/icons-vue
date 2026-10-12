<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xz8w64b_z"/><path class="w-0hx9rsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:campaign-sign-sharp" /></template>
<style>
.w-0hx9rsv {
  d: path("m8.14 6.57l.62 1.37l.14.32l.35.04l1.49.16l.35.04l-.26.23l-1.12 1.01l-.25.23l.07.35l.31 1.47l.07.34l-.3-.18l-1.31-.75l-.3-.17l-.3.17l-1.31.75l-.3.18l.07-.34l.31-1.47l.07-.35l-.25-.23l-1.12-1.01l-.26-.23l.35-.04l1.49-.16l.35-.04l.14-.32l.62-1.37l.14-.32zM13 7.75h4.5M13 11h4.5M7 14.75v6.5m10-6.5v6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xz8w64b_z {
  d: path("M2.75 3.75h18.5v11H2.75z");
}

</style>
