<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lq-vfcc-t"/><path class="t1u28vndk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-connection-fill" /></template>
<style>
.lq-vfcc-t {
  d: path("M6 9V14C6 16.2091 7.79086 18 10 18H11M13 6H14C16.2091 6 18 7.79086 18 10V15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t1u28vndk {
  fill: currentColor;
  d: path("M22 18C22 15.7909 20.2091 14 18 14C15.7909 14 14 15.7909 14 18C14 20.2091 15.7909 22 18 22C20.2091 22 22 20.2091 22 18ZM2 5C2 3.34315 3.34315 2 5 2H7C8.65685 2 10 3.34315 10 5V7C10 8.65685 8.65685 10 7 10H5C3.34315 10 2 8.65685 2 7V5Z");
  stroke: none;
}

</style>
