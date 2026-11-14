<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3wixnhae"/><path class="nmjjwaces"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:folder-pin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmjjwaces {
  d: path("M12 9.5za1 1 0 0 1 1 1v.585a1.5 1.5 0 0 0 .214.771l.536.894a.825.825 0 0 1-.708 1.25h-2.084a.825.825 0 0 1-.708-1.25l.536-.894a1.5 1.5 0 0 0 .214-.771V10.5a1 1 0 0 1 1-1m0 4.5v2.5");
}

.q3wixnhae {
  d: path("M3 7a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
