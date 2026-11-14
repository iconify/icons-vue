<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bc7-46x5m"/><path class="u18k8kcla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:holi-water-gun" /></template>
<style>
.bc7-46x5m {
  d: path("m4.002 11.978l6.496-3.75a2 2 0 0 1 2.732.732a2 2 0 0 1-.732 2.732l-6.496 3.75a2 2 0 0 1-2.732-.732a2 2 0 0 1 .732-2.732");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u18k8kcla {
  d: path("m6.688 15.046l.397-.229a1.435 1.435 0 0 1 2.076.783l.679 2.007a1.5 1.5 0 0 1-.671 1.78l-.342.198a1.4 1.4 0 0 1-2.002-.7l-.783-1.991a1.5 1.5 0 0 1 .646-1.848m5.16-2.979l1.299-.75a1.25 1.25 0 0 1 1.708.458a1.25 1.25 0 0 1-.458 1.707l-1.299.75a1.25 1.25 0 0 1-1.707-.457a1.25 1.25 0 0 1 .457-1.708M14 2c.75 1 1.25 1.5 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.75.5-1.25 1.25-2.25m5.25 0C20 3 20.5 3.5 20.5 4.25a1.25 1.25 0 0 1-2.5 0C18 3.5 18.5 3 19.25 2M20 8.25c.75 1 1.25 1.5 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.75.5-1.25 1.25-2.25");
}

</style>
