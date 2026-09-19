<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6vghgg5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:documents" /></template>
<style>
.p6vghgg5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.364 4.51a1.994 1.994 0 0 0-1.945 1.994v35.002a1.995 1.995 0 0 0 1.944 1.994h27.224a1.994 1.994 0 0 0 1.994-1.994V14.472h-7.977a1.995 1.995 0 0 1-1.945-1.995V4.5Zm19.205 0l9.962 9.962m-23.693 8.456h16.274M15.838 34.994h16.274m-16.274-6.033h16.274");
}

</style>
