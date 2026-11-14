<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9tpbybox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gated-entrance" /></template>
<style>
.t9tpbybox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8h1a1.5 1.5 0 0 1 1.5 1.5V20A1.5 1.5 0 0 1 5 21.5H4A1.5 1.5 0 0 1 2.5 20V9.5A1.5 1.5 0 0 1 4 8M2.5 5.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M19 8h1a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5V9.5A1.5 1.5 0 0 1 19 8m-1.5-2.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M6.5 21.5h11M8.728 11.238l1.5.833A1.5 1.5 0 0 1 11 13.383v3.914a1.5 1.5 0 0 1-1.175 1.464l-1.5.333A1.5 1.5 0 0 1 6.5 17.63v-5.081a1.5 1.5 0 0 1 2.228-1.311m.022.012V19m6.522-7.762l-1.5.833A1.5 1.5 0 0 0 13 13.383v3.914a1.5 1.5 0 0 0 1.175 1.464l1.5.333A1.5 1.5 0 0 0 17.5 17.63v-5.081a1.5 1.5 0 0 0-2.228-1.311m-.022.012V19");
}

</style>
