<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a59w9rb4r"/><path class="p25axz6hm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:creator-badge" /></template>
<style>
.a59w9rb4r {
  d: path("M5.75 9a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p25axz6hm {
  d: path("m9 14.5l-1.5 6l2.25-1L11 21l1-5.75L13 21l1.25-1.5l2.25 1l-1.5-6m-2.625-7.875l.068.203a1.5 1.5 0 0 0 1.274 1.019l.386.038a.493.493 0 0 1 .272.865l-.192.164a1.5 1.5 0 0 0-.488 1.465l.055.246a.483.483 0 0 1-.727.514l-.228-.142a1.5 1.5 0 0 0-1.59 0l-.228.142a.483.483 0 0 1-.727-.514l.055-.246a1.5 1.5 0 0 0-.488-1.465l-.192-.164a.493.493 0 0 1 .272-.865l.386-.038a1.5 1.5 0 0 0 1.274-1.019l.068-.203a.395.395 0 0 1 .75 0");
}

</style>
