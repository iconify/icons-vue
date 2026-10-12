<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="okmv4bgms"/><path class="f5jg_vb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compass-marine" /></template>
<style>
.f5jg_vb3q {
  d: path("m12.1 5.39l.86 3.16q.1.39.49.49l3.16.86q.39.1 0 .2l-3.16.86q-.39.1-.49.49l-.86 3.16q-.1.39-.2 0l-.86-3.16q-.1-.39-.49-.49l-3.16-.86q-.39-.1 0-.2l3.16-.86q.39-.1.49-.49l.86-3.16q.1-.39.2 0M9.35 17.25h5.3q.6 0 .78.57l.89 2.86q.18.57-.42.57H8.1q-.6 0-.42-.57l.89-2.86q.18-.57.78-.57");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.okmv4bgms {
  d: path("M12 2.75a7.25 7.25 0 1 0 0 14.5a7.25 7.25 0 1 0 0-14.5");
}

</style>
