<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jphxtcb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cloud-download-sharp" /></template>
<style>
.jphxtcb3l {
  fill: currentColor;
  d: path("M6.5 20q-2.275 0-3.887-1.575T1 14.575q0-1.95 1.175-3.475T5.25 9.15q.575-2.025 2.138-3.4T11 4.075v8.075L9.4 10.6L8 12l4 4l4-4l-1.4-1.4l-1.6 1.55V4.075q2.575.35 4.288 2.313T19 11q1.725.2 2.863 1.488T23 15.5q0 1.875-1.312 3.188T18.5 20z");
}

</style>
