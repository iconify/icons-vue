<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhz3kfbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cfo" /></template>
<style>
.zhz3kfbmt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 6.5q0-1.968 1.391-3.359T9.5 1.75t3.359 1.391T14.25 6.5t-1.391 3.359T9.5 11.25T6.141 9.859T4.75 6.5m-.68 7.761Q1.75 15.885 1.75 18.5q0 1.75 1.75 1.75h9.019Q12 19.232 12 18q0-2.071 1.464-3.536q.365-.364.767-.637Q12.262 12.75 9.5 12.75q-3.272 0-5.43 1.511M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906m-4 .5q0 .264-.04.488Q17.111 19 17 19q-1 0-1-1t1-1h.035q.215.704.215 1.5");
}

</style>
