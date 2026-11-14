<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj3t8yvtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bookmark-heart" /></template>
<style>
.mj3t8yvtd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.375 2.25h-6.75q-1.398 0-2.386.989q-.989.988-.989 2.386V17.25q0 1.622 1.451 2.348t2.749-.248l1.425-1.069q1.125-.844 2.25 0l1.425 1.069q1.298.973 2.749.248q1.451-.726 1.451-2.348V5.625q0-1.398-.989-2.386q-.988-.989-2.386-.989m-3.791 10.374Q8.25 10.401 8.25 8.25q0-2.5 2.25-2.5q.89 0 1.5.523q.61-.523 1.5-.523q2.25 0 2.25 2.5q0 2.151-3.334 4.374q-.092.062-.199.094q-.106.032-.217.032t-.217-.032t-.199-.094");
}

</style>
