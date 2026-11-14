<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g68vw6bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:canvas-panel" /></template>
<style>
.g68vw6bvs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 2.25H5.25q-2.5 0-2.5 2.5v14.5q0 1.036.732 1.768t1.768.732h13.5q1.036 0 1.768-.732t.732-1.768V4.75q0-2.5-2.5-2.5M8 5.25h8q2.25 0 2.25 2.25v9q0 2.25-2.25 2.25H8q-2.25 0-2.25-2.25v-9q0-2.25 2.25-2.25");
}

</style>
