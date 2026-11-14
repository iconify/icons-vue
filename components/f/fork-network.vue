<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyaejd0rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fork-network" /></template>
<style>
.lyaejd0rm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q8.75 1.75 8.75 5q0 2.85 2.5 3.201v2.549H7q-2.75 0-2.75 2.75v2.81q-2 .345-2 2.69q0 2.75 2.75 2.75T7.75 19q0-2.345-2-2.69V13.5q0-1.25 1.25-1.25h4.25v4.06q-2 .345-2 2.69q0 2.75 2.75 2.75T14.75 19q0-2.345-2-2.69v-4.06H17q1.25 0 1.25 1.25v2.81q-2 .345-2 2.69q0 2.75 2.75 2.75T21.75 19q0-2.345-2-2.69V13.5q0-2.75-2.75-2.75h-4.25V8.201q2.5-.351 2.5-3.201q0-3.25-3.25-3.25");
}

</style>
