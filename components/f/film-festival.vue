<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6-vjibfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-festival" /></template>
<style>
.e6-vjibfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 17.75A6.5 6.5 0 0 1 8.75 6m-1 10.5L5 16.75m.5-4.25L3.25 11m3-2.75l-.5-2.75m8 12.25A6.5 6.5 0 0 0 15.25 6m1 10.5l2.75.25m-.5-4.25l2.25-1.5m-3-2.75l.5-2.75m-5.875 3.125l.068.203a1.5 1.5 0 0 0 1.274 1.019l.386.038a.493.493 0 0 1 .272.865l-.192.164a1.5 1.5 0 0 0-.488 1.465l.055.246a.483.483 0 0 1-.727.514l-.228-.142a1.5 1.5 0 0 0-1.59 0l-.228.142a.483.483 0 0 1-.727-.514l.055-.246a1.5 1.5 0 0 0-.488-1.465l-.192-.164a.493.493 0 0 1 .272-.865l.386-.038a1.5 1.5 0 0 0 1.274-1.019l.068-.203a.395.395 0 0 1 .75 0");
}

</style>
