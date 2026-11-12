<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="seyxj1wqc"/><path class="tbxotkq_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.seyxj1wqc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14.081 18.182a2.8 2.8 0 0 1-4.162 0l-6.393-7.103a3 3 0 0 1 .109-4.128l1.486-1.487A5 5 0 0 1 8.657 4h6.686c1.326 0 2.598.527 3.536 1.464l1.486 1.487a3 3 0 0 1 .109 4.128Z");
}

.tbxotkq_g {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16.5 14l-3.162 3.513a1.8 1.8 0 0 1-2.676 0L4.27 10.41a2 2 0 0 1 .073-2.752l1.486-1.486A4 4 0 0 1 8.657 5h6.686a4 4 0 0 1 2.829 1.172l1.486 1.486a2 2 0 0 1 .073 2.752zM8 9l2 2");
}

</style>
