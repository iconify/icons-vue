<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="htmtp_6gv"/><circle class="ql82ezkup"/><path class="cyagnluem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-coin" /></template>
<style>
.cyagnluem {
  d: path("M14.63 5.77c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htmtp_6gv {
  d: path("M2.75 13.75v7.5m3-6.5h2.5l2.1-1.1a2 2 0 0 1 .95-.25h2.45a1.5 1.5 0 0 1 0 3H11.5m-5.75 4.35h6.6a3 3 0 0 0 1.85-.65l5.6-4.4a1.5 1.5 0 0 0-1.85-2.35l-3.2 2.5");
}

.ql82ezkup {
  cx: 13.5px;
  cy: 6.75px;
  r: 4px;
}

</style>
