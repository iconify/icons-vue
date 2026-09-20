<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="iks8dcxjn"/><path class="oy1v25e7y"/><path class="skbifdbcx"/><path class="zj4mz4frt"/><path class="shm5lmr1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-merge-duotone-thin" /></template>
<style>
.ft030md1w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iks8dcxjn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 11v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oy1v25e7y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 15 -4 -4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.shm5lmr1k {
  d: path("m21 15 -4 -4h-4");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.zj4mz4frt {
  d: path("M21 11v10");
}

</style>
