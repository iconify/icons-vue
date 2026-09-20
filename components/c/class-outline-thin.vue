<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzpsuduik"/><path class="vhnbtvbtn"/><path class="pzk-ur7_u"/><path class="dj-qtcbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:class-outline-thin" /></template>
<style>
.dj-qtcbxo {
  d: path("M6 16.5h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.pzk-ur7_u {
  d: path("M6 12.5h7");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
