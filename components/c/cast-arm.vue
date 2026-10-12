<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2brkouf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cast-arm" /></template>
<style>
.ng2brkouf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.44 16.02l7.08-7.08q.71-.71 1.43-1.4l.15-.15q.72-.69 1.58-1.2l.76-.46q.86-.51 1.57.2l1.06 1.06q.71.71-.15 1.22l-.76.46q-.86.51-1.06 1.49l-.13.63q-.2.98-.91 1.69l-7.08 7.08q-.71.71-1.42 0l-2.12-2.12q-.71-.71 0-1.42m2.12-2.12l3.54 3.54m-1.07-6.01l3.54 3.54");
}

</style>
