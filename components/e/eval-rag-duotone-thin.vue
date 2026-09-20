<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ph4toqkti"/><path class="s7h04rdua"/><path class="qxwxnhbhy"/><path class="olma08bid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eval-rag-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olma08bid {
  d: path("m13 17 2.5 2.5L20 15");
}

.ph4toqkti {
  fill: currentColor;
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qxwxnhbhy {
  d: path("M12.5 12.5 16 16");
}

.s7h04rdua {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
}

</style>
