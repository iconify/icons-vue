<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="zdmqrqb_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fossil" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdmqrqb_e {
  d: path("M12 11c.14-.01.55-.17.83-.08c.27.09.65.32.83.64c.18.31.33.81.26 1.24c-.07.42-.32.98-.7 1.31s-1.01.64-1.59.66c-.57.02-1.34-.15-1.86-.54c-.52-.38-1.07-1.08-1.26-1.77c-.18-.7-.18-1.67.13-2.4c.32-.73.98-1.56 1.74-1.97c.76-.42 1.88-.68 2.81-.53c.92.15 2.05.69 2.74 1.42c.69.74 1.29 1.94 1.38 3.02c.1 1.08-.18 2.48-.81 3.45s-1.78 1.97-2.94 2.38c-1.16.4-2.77.48-4.01.07c-1.23-.4-2.83-2.1-3.4-2.53");
}

</style>
