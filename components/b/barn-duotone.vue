<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lq3nljotz"/><path class="mhhm0fq-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barn-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lq3nljotz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 21h-5v-3a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 1.999V21H4V10.667c0-.433.14-.854.4-1.2l2.365-3.154c.155-.207.349-.381.571-.515l3.635-2.181a2 2 0 0 1 2.058 0l3.635 2.181c.222.134.416.308.571.515L19.6 9.467c.26.346.4.767.4 1.2ZM10 10a2 2 0 1 0 3.999.001A2 2 0 0 0 10 10");
}

.mhhm0fq-j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 21H4V10.667a2 2 0 0 1 .4-1.2l2.365-3.154a2 2 0 0 1 .57-.515l3.636-2.18a2 2 0 0 1 2.058 0l3.635 2.18a2 2 0 0 1 .571.515L19.6 9.467a2 2 0 0 1 .4 1.2zM3 21h18M9 21v-3a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v3m-5-11a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
