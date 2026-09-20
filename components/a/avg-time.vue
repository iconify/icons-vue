<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgubxmb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:avg-time" /></template>
<style>
.qgubxmb3r {
  fill: currentColor;
  d: path("M9.385 2.5v-1h5.23v1zM10 15.866L8.439 12.78q-.068-.14-.183-.21Q8.14 12.5 8 12.5H4.012q.182-3.164 2.482-5.332T12 5q1.454 0 2.812.52t2.492 1.469l1.092-1.093l.708.708l-1.092 1.092q.857 1.031 1.38 2.251q.524 1.22.597 2.553h-3.672l-1.86-3.72q-.14-.286-.447-.286q-.308 0-.448.287zm-3.506 2.966q-2.3-2.169-2.482-5.332h3.67l1.86 3.72q.14.286.449.296q.307.009.448-.277L14 10.135l1.562 3.084q.067.14.182.21q.116.071.256.071h3.989q-.183 3.164-2.483 5.332T12 21t-5.506-2.168");
}

</style>
