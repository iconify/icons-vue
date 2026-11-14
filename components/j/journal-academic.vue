<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qujelwbbn"/><path class="s28sg-6_t"/><path class="lszvceb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:journal-academic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lszvceb3m {
  d: path("M12 8v2.5q2 1.25 4 0V8");
}

.qujelwbbn {
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v12a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18V6a3.5 3.5 0 0 1 3.5-3.5m0 0v19");
}

.s28sg-6_t {
  d: path("m14.711 5.883l.914.492a.994.994 0 0 1 0 1.75l-.914.492a1.5 1.5 0 0 1-1.422 0l-.914-.492a.994.994 0 0 1 0-1.75l.914-.492a1.5 1.5 0 0 1 1.422 0");
}

</style>
