<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fl6kv5jns"/><path class="kjp3lpb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-left-duotone" /></template>
<style>
.fl6kv5jns {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 19h-8l-6-6a1.415 1.415 0 0 1 0-2l6-6h8c.369 0 .369.631 0 1l-5 5a1.415 1.415 0 0 0 0 2l5 5c.369.369.369 1 0 1");
}

.ft5dv1b6b {
  fill: none;
}

.kjp3lpb1y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 19h4c.369 0 .369-.631 0-1l-5-5a1.414 1.414 0 0 1 0-2l5-5c.369-.369.369-1 0-1h-8l-6 6a1.414 1.414 0 0 0 0 2l6 6z");
}

</style>
