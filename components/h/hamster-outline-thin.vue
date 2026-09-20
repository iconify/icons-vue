<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3lxg1bko"/><path class="jw-230sxh"/><path class="rckmicclj"/><path class="so0bhmbof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hamster-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jw-230sxh {
  d: path("M6 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rckmicclj {
  d: path("M14 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s3lxg1bko {
  d: path("M12 19c-4 0 -7 -3 -7 -6 0 -4 3 -6 7 -6s7 2 7 6c0 3 -3 6 -7 6");
}

.so0bhmbof {
  d: path("M11 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
