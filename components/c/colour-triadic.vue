<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqmkrmf2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-triadic" /></template>
<style>
.xqmkrmf2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 7.5q0-2.382 1.684-4.066T12 1.75t4.066 1.684T17.75 7.5q0 1.245-.46 2.299q1.878.237 3.276 1.635q1.684 1.684 1.684 4.066t-1.684 4.066T16.5 21.25t-4.066-1.684q-.233-.233-.434-.48q-.201.247-.434.48Q9.882 21.25 7.5 21.25t-4.066-1.684T1.75 15.5t1.684-4.066q1.398-1.398 3.276-1.635q-.46-1.054-.46-2.299");
}

</style>
