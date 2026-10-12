<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it-qfxbvy"/><path class="wmgztcjui"/><rect class="ayfqfi6fr"/><path class="lpkyjcbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-lock" /></template>
<style>
.ayfqfi6fr {
  width: 6.5px;
  height: 5px;
  x: 14.25px;
  y: 16.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it-qfxbvy {
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

.lpkyjcbgj {
  d: path("M15.75 16.25V15a1.75 1.75 0 0 1 3.5 0v1.25");
}

.wmgztcjui {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4");
}

</style>
