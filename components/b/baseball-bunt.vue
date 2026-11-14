<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxgj8ybhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baseball-bunt" /></template>
<style>
.fxgj8ybhe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.801 5.25H4.5q-.932 0-1.591.659T2.25 7.5q0 2.25 2.25 2.25h5.301q.142 0 .282.021l8.284 1.26q1.532.234 2.708-.776q1.175-1.01 1.175-2.56v-.39q0-1.55-1.175-2.56t-2.708-.776l-8.284 1.26q-.14.021-.282.021M11.75 17q0-1.76 1.245-3.005T16 12.75t3.005 1.245T20.25 17t-1.245 3.005T16 21.25t-3.005-1.245T11.75 17");
}

</style>
