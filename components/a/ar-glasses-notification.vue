<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef_s98btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ar-glasses-notification" /></template>
<style>
.ef_s98btu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75q1.968 0 3.359 1.391q.559.56.894 1.212Q11.36 5 12 5t1.247.353q.335-.652.894-1.212Q15.532 2.75 17.5 2.75t3.359 1.391T22.25 7.5t-1.391 3.359T17.5 12.25t-3.359-1.391T12.75 7.5q0-.325.038-.634q-.788-.641-1.576 0q.038.309.038.634q0 1.968-1.391 3.359T6.5 12.25t-3.359-1.391T1.75 7.5t1.391-3.359T6.5 2.75m9.5 11.5h4.5q1.75 0 1.75 1.75v3q0 1.75-1.75 1.75h-2.792l-2.322 1.393q-.063.038-.133.063t-.143.036t-.146.007q-.074-.003-.146-.021t-.138-.05q-.067-.031-.126-.075q-.06-.044-.109-.099q-.05-.055-.088-.118q-.107-.178-.107-.386V16q0-1.75 1.75-1.75m0 1.5q-.25 0-.25.25v4.175l1.364-.818q.178-.107.386-.107h3q.25 0 .25-.25v-3q0-.25-.25-.25z");
}

</style>
