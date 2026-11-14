<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-pzt_91b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:amino-acid" /></template>
<style>
.g-pzt_91b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.338 6.75q.189-.771.79-1.372q.879-.88 2.122-.88t2.122.88q.879.879.878 2.121q.001 1.244-.878 2.123t-2.122.88q-1.243 0-2.122-.88q-.601-.601-.79-1.372h-1.392q-.294 1.902-2.196 2.196v3.108Q15 13.902 15 16.5q0 3-3 3t-3-3q0-2.598 2.25-2.946v-3.108q-1.902-.294-2.196-2.196H7.696Q7.348 10.5 4.75 10.5q-3 0-3-3t3-3q2.598 0 2.946 2.25h1.358Q9.402 4.5 12 4.5t2.946 2.25z");
}

</style>
