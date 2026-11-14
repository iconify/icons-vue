<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot_9yolrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-body" /></template>
<style>
.ot_9yolrd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.495 6.25H18q1.76 0 3.005 1.245T22.25 10.5V17q0 1.76-1.245 3.005T18 21.25H6q-1.76 0-3.005-1.245T1.75 17v-6.5q0-1.76 1.245-3.005T6 6.25h1.505l1.306-3.045q.043-.102.114-.186q.07-.085.162-.145q.092-.061.197-.092q.106-.032.216-.032h5q.11 0 .216.032q.105.031.197.092q.092.06.162.145t.114.186zm-7.358 0h5.726l-.858-2h-4.01zM7.5 13.75q0 1.864 1.318 3.182T12 18.25t3.182-1.318T16.5 13.75t-1.318-3.182T12 9.25t-3.182 1.318T7.5 13.75");
}

</style>
