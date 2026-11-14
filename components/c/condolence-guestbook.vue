<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e4gzrehpu"/><path class="ay8qsdbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:condolence-guestbook" /></template>
<style>
.ay8qsdbrm {
  d: path("m15.122 12.653l.098-1.073a1.5 1.5 0 0 1 .197-.617l3.741-6.443a1.14 1.14 0 0 1 1.592-.395a1.22 1.22 0 0 1 .408 1.645l-3.733 6.429a1.5 1.5 0 0 1-.465.494l-.835.557a.647.647 0 0 1-1.003-.597");
}

.e4gzrehpu {
  d: path("M21.5 10.757V18.5c-3-1-6.5-.5-9.5 1.5c-3-2-6.5-2.5-9.5-1.5v-11C5.5 6.5 9 7 12 9a12.4 12.4 0 0 1 1.932-1.055M12 9v11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
