<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8vy5h5pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-loop-limit-duotone" /></template>
<style>
.k8vy5h5pv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.5858 9.4142L6.4142 5.5858C6.7893 5.2107 7.298 5 7.8284 5L16.1716 5C16.702 5 17.2107 5.2107 17.5858 5.5858L21.4142 9.4142C21.7893 9.7893 22 10.298 22 10.8284L22 16C22 17.6569 20.6569 19 19 19L5 19C3.3431 19 2 17.6569 2 16L2 10.8284C2 10.298 2.2107 9.7893 2.5858 9.4142Z");
}

</style>
