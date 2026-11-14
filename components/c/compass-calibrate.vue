<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs-wh9c-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compass-calibrate" /></template>
<style>
.qs-wh9c-a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 7.25q0-2.382 1.684-4.066T12 1.5t4.066 1.684T17.75 7.25t-1.684 4.066T12 13t-4.066-1.684T6.25 7.25M12 19.53Q9.942 22 6.313 22Q1.75 22 1.75 18.25t4.563-3.75q3.629 0 5.687 2.47q2.058-2.47 5.688-2.47q4.562 0 4.562 3.75T17.688 22q-3.63 0-5.688-2.47m.905-1.28q1.651 2.25 4.783 2.25q3.062 0 3.062-2.25T17.688 16q-3.132 0-4.783 2.25m-1.81 0Q9.444 16 6.313 16Q3.25 16 3.25 18.25t3.063 2.25q3.131 0 4.782-2.25");
}

</style>
