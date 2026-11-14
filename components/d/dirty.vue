<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jutj8wbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dirty" /></template>
<style>
.jutj8wbxh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 2Q17.5 2 17.5 4.25t2.25 2.25T22 4.25T19.75 2M10 3.75q1.882 0 3.77 1.28q1.061.72 1.73.72q2.432 0 2.743 2.338q.222 1.665-.801 2.978q.989 1.715.189 3.657q-.934 2.269-3.315 2.072q-1.312 1.455-3.503 1.455q-2.196 0-3.206-1.446q-2.353.188-3.394-1.764q-1.009-1.891.327-3.589q-1.221-1.897-.191-3.698q.972-1.701 2.663-1.589Q8.024 3.75 10 3.75m6.75 15q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>
