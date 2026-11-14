<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpsfqhbyw"/><path class="josl_757c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:help-badge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.josl_757c {
  d: path("M9.25 9.25c0-1.55 1.25-2.5 2.75-2.5c1.6 0 2.75 1.05 2.75 2.5c0 2-2.75 2.25-2.75 4m0 3.5h.01");
}

.wpsfqhbyw {
  d: path("m13.068 3.141l.29.242a2.19 2.19 0 0 0 1.775.475l.372-.064a1.67 1.67 0 0 1 1.849 1.067l.131.355a2.19 2.19 0 0 0 1.299 1.299l.355.131a1.67 1.67 0 0 1 1.067 1.849l-.064.372a2.19 2.19 0 0 0 .475 1.775l.242.29a1.67 1.67 0 0 1 0 2.136l-.242.29a2.19 2.19 0 0 0-.475 1.775l.064.372a1.67 1.67 0 0 1-1.067 1.849l-.355.131a2.19 2.19 0 0 0-1.299 1.299l-.131.355a1.67 1.67 0 0 1-1.849 1.067l-.372-.064a2.19 2.19 0 0 0-1.775.475l-.29.242a1.67 1.67 0 0 1-2.136 0l-.29-.242a2.19 2.19 0 0 0-1.775-.475l-.372.064a1.67 1.67 0 0 1-1.849-1.067l-.131-.355a2.19 2.19 0 0 0-1.299-1.299l-.355-.131a1.67 1.67 0 0 1-1.067-1.849l.064-.372a2.19 2.19 0 0 0-.475-1.775l-.242-.29a1.67 1.67 0 0 1 0-2.136l.242-.29a2.19 2.19 0 0 0 .475-1.775l-.064-.372a1.67 1.67 0 0 1 1.067-1.849l.355-.131a2.19 2.19 0 0 0 1.299-1.299l.131-.355a1.67 1.67 0 0 1 1.849-1.067l.372.064a2.19 2.19 0 0 0 1.775-.475l.29-.242a1.67 1.67 0 0 1 2.136 0");
}

</style>
