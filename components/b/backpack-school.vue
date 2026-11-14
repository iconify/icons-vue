<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t890mxpoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:backpack-school" /></template>
<style>
.t890mxpoa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 5.438Q16.46 6 17.48 7.02q2.27 2.27 2.27 5.48v2q0 3.21-2.27 5.48T12 22.25t-5.48-2.27t-2.27-5.48v-2q0-3.21 2.27-5.48Q7.54 6 8.75 5.438V4.5q0-3.25 3.25-3.25t3.25 3.25zm-5-.504q.837-.184 1.75-.184t1.75.184V4.5q0-1.75-1.75-1.75T10.25 4.5zM7.25 16q0 3.25 3.25 3.25h3q3.25 0 3.25-3.25t-3.25-3.25h-3q-3.25 0-3.25 3.25");
}

</style>
