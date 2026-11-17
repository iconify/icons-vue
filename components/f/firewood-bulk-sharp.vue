<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hze9_2boy"/><path class="it18heskr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewood-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hze9_2boy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5c0-.329.098-.647.27-.926c.765-1.246 2.923-1.719 4.255-1.907Q10.757 1.997 12 2q1.243-.003 2.475.167c1.187.167 2.713.513 3.672 1.269c.489.386.853.922.853 1.564v3.586l.707.707a2.414 2.414 0 0 1 0 3.414l-.707.707V19c0 .329-.098.647-.27.926c-.765 1.246-2.923 1.719-4.255 1.907q-1.232.17-2.475.167a18 18 0 0 1-2.475-.167c-1.187-.167-2.713-.513-3.672-1.269C5.364 20.178 5 19.642 5 19v-3.586l-.707-.707a2.414 2.414 0 0 1 0-3.414L5 10.586Z");
}

.it18heskr {
  d: path("M6.996 4.908a.6.6 0 0 0 .095.085c.285.225.642.359.982.473a10 10 0 0 0 1.731.387Q10.897 6.003 12 6q1.103.003 2.196-.147a10 10 0 0 0 1.731-.387c.34-.114.697-.248.982-.473a.6.6 0 0 0 .095-.085A1 1 0 0 1 19 5c0 .329-.098.647-.27.926c-.765 1.246-2.923 1.719-4.255 1.907Q13.243 8.003 12 8a18 18 0 0 1-2.475-.167c-1.332-.188-3.49-.661-4.255-1.907A1.77 1.77 0 0 1 5 5a1 1 0 0 1 1.996-.092M11 12v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
