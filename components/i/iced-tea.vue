<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="df6l5_iul"/><path class="qa2c-vbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:iced-tea" /></template>
<style>
.df6l5_iul {
  d: path("M6.422 5.5h11.156a1.75 1.75 0 0 1 1.743 1.913l-1.172 12.5a1.75 1.75 0 0 1-1.743 1.587H7.594a1.75 1.75 0 0 1-1.743-1.587l-1.172-12.5A1.75 1.75 0 0 1 6.422 5.5m8.078 7l3-10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qa2c-vbqm {
  d: path("M9.25 9h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-.5A1.5 1.5 0 0 1 9.25 9m3 6.25h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
