<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i3r0heblp"/><path class="bjl4oq5wt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:highlighter-off" /></template>
<style>
.bjl4oq5wt {
  d: path("m9.172 14.828l.53.531a.75.75 0 0 1 0 1.06a1.21 1.21 0 0 1-1.242.294l-1.047-.35a.927.927 0 0 1-.363-1.535a1.5 1.5 0 0 1 2.122 0M3.5 3.5l17 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3r0heblp {
  d: path("m11.874 7.884l2.866-2.867q.091-.091.191-.173t.207-.153t.221-.133t.233-.11q.119-.049.242-.087t.25-.062t.255-.038t.257-.013t.257.013q.129.013.255.038q.127.025.25.062q.123.038.242.087q.12.049.233.11t.221.133q.107.071.207.153t.191.173l.531.531q.091.091.173.191t.153.207t.133.221t.11.233t.087.242q.037.123.062.25q.025.126.038.255q.013.128.013.257t-.013.257t-.038.255t-.062.25t-.087.242t-.11.233t-.133.221t-.153.207t-.173.191l-2.851 2.85m-4.412 3.566l-.167.083q-.105.053-.217.088q-.112.036-.228.053t-.233.018q-.118-.001-.233-.02t-.228-.055q-.111-.037-.216-.09q-.104-.054-.199-.123t-.178-.152l-1.299-1.299q-.083-.083-.152-.178t-.123-.199q-.053-.105-.09-.216q-.036-.112-.055-.228q-.019-.115-.02-.233q0-.117.018-.233t.053-.228t.088-.217l.075-.15");
}

</style>
