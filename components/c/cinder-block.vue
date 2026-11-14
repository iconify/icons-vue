<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k29tyfq3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cinder-block" /></template>
<style>
.k29tyfq3o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 3.25H4.25q-1.036 0-1.768.732T1.75 5.75v12.5q0 2.5 2.5 2.5h15.5q1.036 0 1.768-.732t.732-1.768V5.75q0-1.036-.732-1.768T19.75 3.25m-11 3Q11 6.25 11 8.5v1.75q0 2.25-2.25 2.25H7q-2.25 0-2.25-2.25V8.5q0-2.25 2.25-2.25zm6.5 0H17q2.25 0 2.25 2.25v1.75q0 2.25-2.25 2.25h-1.75Q13 12.5 13 10.25V8.5q0-2.25 2.25-2.25");
}

</style>
