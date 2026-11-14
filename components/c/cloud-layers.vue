<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvjw1bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-layers" /></template>
<style>
.jtvjw1bru {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 7.75q-.932 0-1.591-.659T3.75 5.5q0-2.25 2.25-2.25h2.12Q9.2 1.908 11 1.908t2.88 1.342H16q2.25 0 2.25 2.25q0 .932-.659 1.591T16 7.75zm.75 5Q6.75 15 9 15h11q2.25 0 2.25-2.25T20 10.5h-1.62Q17.3 9.158 15.5 9.158T12.62 10.5H9q-2.25 0-2.25 2.25M4 22.25q-2.25 0-2.25-2.25T4 17.75h2.62q1.08-1.342 2.88-1.342t2.88 1.342H15q2.25 0 2.25 2.25T15 22.25z");
}

</style>
