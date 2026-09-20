<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t7jqbzdsw"/><path class="eaep8gb-r"/><path class="xysg8jnyz"/><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="ov4z8dh4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hallucination-detect-duotone-bold" /></template>
<style>
.eaep8gb-r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.moha5wbmp {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

.ov4z8dh4a {
  d: path("m8 13.5 2.5 -2.5 2.5 2.5 2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t7jqbzdsw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xysg8jnyz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 13.5 2.5 -2.5 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yix-58bnj {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
