<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3jr99boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:circles" /></template>
<style>
.v3jr99boq {
  fill: currentColor;
  d: path("M17 2.154q2.02 0 3.433 1.413T21.846 7t-1.413 3.433T17 11.846t-3.433-1.413T12.154 7t1.413-3.433T17 2.154m.004 11.698q.373 0 .727-.044t.715-.146q-.256 2.91-2.39 4.874T11 20.5q-1.548 0-2.916-.587t-2.389-1.608t-1.608-2.389T3.5 13q0-2.921 1.965-5.046q1.964-2.125 4.874-2.42q-.103.368-.144.74q-.041.373-.041.745q.012 2.85 2.008 4.842t4.842 1.991");
}

</style>
