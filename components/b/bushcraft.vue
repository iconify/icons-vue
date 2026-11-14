<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdt-gufed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bushcraft" /></template>
<style>
.zdt-gufed {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m17.591 3.655l-6.303 1.689q-1.226.329-1.575 1.163q-.52-.084-1.193.097L4.173 7.768Q2 8.351 2.583 10.523q.241.9 1.048 1.366t1.707.225l4.346-1.165q.839-.224 1.301-.94q.758.389 1.597.164l4.714-1.263q.899-.241 1.364-1.048l.927-1.605q.594-1.027-.128-1.968t-1.868-.634M6 14.5q-3.25 0-3.25 3.75T6 22h12.5q3.25 0 3.25-3.75T18.5 14.5zm12.5 6H8.811q.439-.872.439-2.25T8.811 16H18.5q1.75 0 1.75 2.25T18.5 20.5");
}

</style>
