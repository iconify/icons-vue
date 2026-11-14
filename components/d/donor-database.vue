<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4uv3b5ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:donor-database" /></template>
<style>
.i4uv3b5ff {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5q0-3.25 7.5-3.25T17.25 5v6.542q-2.087.246-2.722 1.944Q12.732 14 9.75 14q-2.93 0-5.033-.779q-.544-.201-.967-.433V17.5q0 .514 1.488 1.064q1.85.686 4.512.686q1.89 0 3.184-.174q-.32.671-.404 1.535q-1.23.139-2.78.139q-2.93 0-5.033-.779Q2.25 19.058 2.25 17.5zm13.5 2.257q-1.854.993-6 .993q-2.93 0-5.033-.779q-.544-.201-.967-.433v3.712q0 .514 1.488 1.064q1.85.686 4.512.686q6 0 6-1.75zm-.25 7.993q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T18 17.75q-2.5 0-2.5-2.5m1.5 0q0 1 1 1q.414 0 .707-.293T19 15.25t-.293-.707T18 14.25q-1 0-1 1M18 18q-4.25 0-4.25 3.25q0 1.25 1.25 1.25h6q1.25 0 1.25-1.25Q22.25 18 18 18m2.735 3h-5.47q.189-1.5 2.735-1.5t2.735 1.5");
}

</style>
