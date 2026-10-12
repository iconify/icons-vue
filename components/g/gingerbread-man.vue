<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="ul2ad0bhm"/><path class="g455cibsq"/><path class="s84l2-b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gingerbread-man" /></template>
<style>
.g455cibsq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 10h3.5q1 0 1.95.32l3.35 1.11q.95.32.66 1.28l-.17.58q-.29.96-1.27.79l-2.29-.41q-.98-.17-.76.81l1.31 5.79q.22.98-.78.98h-1.5q-1 0-1.36-.93l-.53-1.39q-.36-.93-.72 0l-.53 1.39q-.36.93-1.36.93h-1.5q-1 0-.78-.98l1.31-5.79q.22-.98-.76-.81l-2.29.41q-.98.17-1.27-.79l-.17-.58q-.29-.96.66-1.28l3.35-1.11q.95-.32 1.95-.32");
}

.s84l2-b-l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.75h.01M12 15.5h.01");
}

.ul2ad0bhm {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
