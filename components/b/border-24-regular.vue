<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hhjk2-65i"/><path class="k19nuvb3y"/><path class="yr8z9fv3s"/><path class="ly40fwr0r"/><path class="lgxfxabkb"/><path class="c6e-8hgxu"/><path class="yqutgtdzf"/><path class="jnd5vgmin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-24-regular" /></template>
<style>
.c6e-8hgxu {
  d: path("M17.75 3a.75.75 0 0 0 0 1.5h.5c.69 0 1.25.56 1.25 1.25v.5a.75.75 0 0 0 1.5 0v-.5A2.75 2.75 0 0 0 18.25 3h-.5z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.hhjk2-65i {
  d: path("M14 3.75a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h2.5a.75.75 0 0 1 .75.75z");
  fill: currentColor;
}

.jnd5vgmin {
  d: path("M17.75 21a.75.75 0 0 1 0-1.5h.5c.69 0 1.25-.56 1.25-1.25v-.5a.75.75 0 0 1 1.5 0v.5A2.75 2.75 0 0 1 18.25 21h-.5z");
  fill: currentColor;
}

.k19nuvb3y {
  d: path("M4.5 10.75a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 1.5 0v-2.5z");
  fill: currentColor;
}

.lgxfxabkb {
  d: path("M7 3.75A.75.75 0 0 0 6.25 3h-.5A2.75 2.75 0 0 0 3 5.75v.5a.75.75 0 0 0 1.5 0v-.5c0-.69.56-1.25 1.25-1.25h.5A.75.75 0 0 0 7 3.75z");
  fill: currentColor;
}

.ly40fwr0r {
  d: path("M13.25 21a.75.75 0 0 0 0-1.5h-2.5a.75.75 0 0 0 0 1.5h2.5z");
  fill: currentColor;
}

.yqutgtdzf {
  d: path("M7 20.25a.75.75 0 0 1-.75.75h-.5A2.75 2.75 0 0 1 3 18.25v-.5a.75.75 0 0 1 1.5 0v.5c0 .69.56 1.25 1.25 1.25h.5a.75.75 0 0 1 .75.75z");
  fill: currentColor;
}

.yr8z9fv3s {
  d: path("M19.5 10.75a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-1.5 0v-2.5z");
  fill: currentColor;
}

</style>
