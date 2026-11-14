<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojjx57b7q"/><path class="j8ukfzy4v"/><path class="j29wracxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-equity" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j29wracxh {
  d: path("M4.5 17.25a7.5 2 0 0 0 15 0m-9-3.75v-3h3v3");
}

.j8ukfzy4v {
  d: path("M4.5 15v4.5a7.5 2 0 0 0 15 0V15M5.573 8.05l5.5-4.322a1.5 1.5 0 0 1 1.854 0l5.5 4.322A1.5 1.5 0 0 1 19 9.229V12a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 12V9.229a1.5 1.5 0 0 1 .573-1.179");
}

.ojjx57b7q {
  d: path("M4.5 15a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0");
}

</style>
