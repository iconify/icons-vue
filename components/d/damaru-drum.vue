<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdgmriupp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:damaru-drum" /></template>
<style>
.cdgmriupp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.297 2.75h7.406q1.504-.001 2.209 1.328t-.138 2.573l-3.112 4.599h1.905Q16.908 9.5 19 9.5q2.5 0 2.5 2.5T19 14.5q-2.092 0-2.433-1.75h-1.905l3.112 4.599q.843 1.245.138 2.573q-.705 1.329-2.209 1.328H8.297q-1.504.001-2.209-1.328t.138-2.573l3.112-4.599H7.433Q7.092 14.5 5 14.5q-2.5 0-2.5-2.5T5 9.5q2.092 0 2.433 1.75h1.905L6.226 6.651q-.843-1.245-.138-2.573q.705-1.329 2.209-1.328");
}

</style>
