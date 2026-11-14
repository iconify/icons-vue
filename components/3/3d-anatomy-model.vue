<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kbfnbubqi"/><path class="tsm53-xwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:3d-anatomy-model" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kbfnbubqi {
  d: path("M12.133 14.5H4.25c0-3 2.25-4.75 5-4.75c2.285 0 4.225 1.208 4.816 3.338m-1.784 8.266c-.806.257-1.85.396-3.032.396c-2.75 0-4.75-.75-4.75-2V19c0-1.25 2-2 4.75-2c.902 0 1.724.081 2.42.233M6.75 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 9.5V17m9.421-2.415l2 1a1.5 1.5 0 0 1 .829 1.342v2.146a1.5 1.5 0 0 1-.829 1.342l-2 1a1.5 1.5 0 0 1-1.342 0l-2-1a1.5 1.5 0 0 1-.829-1.342v-2.146a1.5 1.5 0 0 1 .829-1.342l2-1a1.5 1.5 0 0 1 1.342 0");
}

.tsm53-xwj {
  d: path("m14.5 16l3.5 1.75L21.5 16M18 17.75v4");
}

</style>
