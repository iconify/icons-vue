<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbprhzqfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:feature-branch" /></template>
<style>
.nbprhzqfs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 4.5q0-2.75 2.75-2.75T9.75 4.5q0 2.345-2 2.69v6.487q1.338-.634 3.869-.948q3.325-.412 4.263-1.124Q14.25 11.118 14.25 9q0-2.75 2.75-2.75T19.75 9q0 2.424-2.136 2.711q-.765 1.881-5.81 2.507Q7.75 14.72 7.75 15.5v1.31q2 .345 2 2.69q0 2.75-2.75 2.75T4.25 19.5q0-2.345 2-2.69V7.19q-2-.345-2-2.69");
}

</style>
