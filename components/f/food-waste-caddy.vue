<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spzmakbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:food-waste-caddy" /></template>
<style>
.spzmakbca {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.193 6.25H19q2.25 0 2.25 2.25q0 1.877-1.565 2.188l-.939 9.387Q18.579 21.75 17 21.75H7q-1.579 0-1.746-1.675l-.939-9.387Q2.75 10.377 2.75 8.5q0-2.25 2.25-2.25h.807Q6.347 2.875 12 2.875t6.193 3.375m-10.829 0Q7.986 4.375 12 4.375t4.636 1.875zm9.89 13.675l.917-9.175H5.829l.917 9.175q.033.325.254.325h10q.221 0 .254-.325M15.25 12Q8 12 8 18.25q0 .149.057.287t.163.243v.001l.006.006h.001q.105.103.24.158q.136.055.283.055Q16 19 16 12.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15.25 12");
}

</style>
