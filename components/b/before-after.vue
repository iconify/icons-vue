<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hbfoyhtqd"/><path class="a_lm3y-ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:before-after" /></template>
<style>
.a_lm3y-ho {
  d: path("M5 6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1.25 5c.25-1.25 1.5-1.75 3-1.75s2.75.5 3 1.75m7.5-7l.823 1.617l1.792.283l-1.284 1.283l.285 1.792l-1.616-.825l-1.616.825l.285-1.792L14.635 6.4l1.792-.283Z");
}

.hbfoyhtqd {
  d: path("M2.5 3H11v8.5H2.5ZM13 3h8.5v8.5H13ZM6.75 17.5h10.5m-2.75-2.75l2.75 2.75l-2.75 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
