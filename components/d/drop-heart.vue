<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8jl2gibv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drop-heart" /></template>
<style>
.e8jl2gibv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 14.5q0-4.796-7.202-12.512q-.017-.019-.036-.036q-.109-.102-.249-.154t-.289-.048q-.149.006-.285.067t-.237.171Q4.25 9.704 4.25 14.5q0 3.21 2.27 5.48T12 22.25t5.48-2.27t2.27-5.48m-8.28 4.28l-2.75-2.75l-.025-.025q-.727-.8-.675-1.879t.85-1.806q.8-.727 1.879-.675q.679.032 1.219.36q1.517-1.18 3.162.315q1.929 1.755.175 3.685l-.025.025l-2.75 2.75q-.052.053-.113.094t-.13.069t-.141.043T12 19t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094");
}

</style>
