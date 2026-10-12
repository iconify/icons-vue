<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sbauagb9i"/><circle class="o19ergbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cherry-blossom" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o19ergbhs {
  cx: 12px;
  cy: 12.25px;
  r: 1.75px;
}

.sbauagb9i {
  d: path("M9.74 8.12L9.57 4.7q-.05-1.1.91-.56l.56.32q.96.54 1.92 0l.56-.32q.96-.54.91.56l-.17 3.42q-.06 1.1.97.71l3.2-1.22q1.03-.39.81.69l-.13.63q-.21 1.08.6 1.82l.47.44q.81.75-.25 1.03l-3.3.9q-1.06.29-.37 1.15l2.14 2.66q.69.86-.4.99l-.65.07q-1.09.13-1.55 1.13l-.26.59q-.46 1-1.06.08l-1.88-2.87q-.6-.92-1.2 0l-1.88 2.87q-.6.92-1.06-.08l-.26-.59q-.46-1-1.55-1.13L6 17.92q-1.09-.13-.4-.99l2.14-2.66q.69-.86-.37-1.15l-3.3-.9q-1.06-.28-.25-1.03l.47-.44q.81-.74.6-1.82l-.13-.63q-.22-1.08.81-.69l3.2 1.22q1.03.39.97-.71");
}

</style>
