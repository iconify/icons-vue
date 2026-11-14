<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxbdc1baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-visor" /></template>
<style>
.qxbdc1baf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 8q0-1.913 2.465-3.146Q11.923 3.75 15 3.75t5.285 1.104Q22.75 6.087 22.75 8v2.5q0 1.913-2.465 3.146q-.835.417-1.795.677q-3.004 3.154-7.865 4.192q-4.52.965-8.125-.308q-.044-.015-.085-.036q-.134-.067-.232-.18q-.097-.112-.145-.254q-.047-.141-.036-.29q.01-.149.077-.282q1.506-3.011 6.502-4.221Q7.25 11.906 7.25 10.5zM15 13.25q2.722 0 4.614-.946q1.576-.788 1.634-1.732q-.422.303-.963.574Q18.077 12.25 15 12.25t-5.285-1.104q-.541-.271-.963-.574q.058.944 1.634 1.732q.223.112.459.211l.049-.007q.097-.014.195-.003q.097.012.189.048q.091.037.17.095t.14.136q1.501.466 3.412.466m0 1.5q-2.436 0-4.327-.692q-5.004.795-6.762 3.011q2.867.733 6.401-.021q3.16-.675 5.435-2.315q-.367.017-.747.017");
}

</style>
