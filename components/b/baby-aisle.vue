<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bopowcm8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-aisle" /></template>
<style>
.bopowcm8o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.314 7.75q.203-1.207 1.05-2.524q.539-.836.637-1.299Q10.037 2 12 2t1.999 1.927q.098.463.637 1.299q.847 1.317 1.05 2.524H16q2.25 0 2.25 2.25q0 1.5-1 2v7.5q0 2.75-2.75 2.75h-5q-2.75 0-2.75-2.75V12q-1-.5-1-2q0-2.25 2.25-2.25zm1.53 0q.193-.797.782-1.712q.735-1.143.864-1.915q.01-.061.01-.123q0-.5.5-.5t.5.5q0 .062.01.123q.129.772.864 1.915q.589.915.782 1.712zM8.25 19.5q0 1.25 1.25 1.25h5q1.25 0 1.25-1.25v-7.25h-7.5z");
}

</style>
