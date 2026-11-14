<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc526xltz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git-merge-base" /></template>
<style>
.cc526xltz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 5q0-2.75 2.75-2.75T8.75 5q0 2.345-2 2.69v.81q0 1.069 2.628 2.602q1.782 1.04 2.622 2.069q.84-1.029 2.622-2.069Q17.25 9.569 17.25 8.5v-.81q-2-.345-2-2.69q0-2.75 2.75-2.75T20.75 5q0 2.345-2 2.69v.81q0 1.931-3.372 3.898Q12.75 13.931 12.75 15v1.31q2 .345 2 2.69q0 2.75-2.75 2.75T9.25 19q0-2.345 2-2.69V15q0-1.069-2.628-2.602Q5.25 10.431 5.25 8.5v-.81q-2-.345-2-2.69");
}

</style>
