<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pddx4yr2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capsule-3d" /></template>
<style>
.pddx4yr2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q2.382 0 4.066 1.684T17.75 7.5V12q0-2.5-5.75-2.5T6.25 12V7.5q0-2.382 1.684-4.066T12 1.75M7.75 12q0 1 4.25 1t4.25-1T12 11t-4.25 1m-1.5 0v4.5q0 2.382 1.684 4.066T12 22.25t4.066-1.684T17.75 16.5V12q0 2.5-5.75 2.5T6.25 12");
}

</style>
