<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t35ikg1yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:binoculars-marine" /></template>
<style>
.t35ikg1yl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 2.25h1.5q1.036 0 1.768.732T9.75 4.75v1.5q0 1.011-.698 1.733q.425.277.807.658q1.118 1.118 1.337 2.609h1.608q.219-1.491 1.337-2.609q.324-.324.68-.573q-.571-.623-.571-1.818v-1.5q0-2.5 2.5-2.5h1.5q2.5 0 2.5 2.5v1.5q0 1.195-.571 1.818q.356.249.68.573Q22.25 10.032 22.25 12v5.5q0 1.968-1.391 3.359T17.5 22.25t-3.359-1.391T12.75 17.5v-4.75h-1.5v4.75q0 1.968-1.391 3.359T6.5 22.25t-3.359-1.391T1.75 17.5V12q0-1.968 1.391-3.359q.324-.324.68-.573q-.571-.623-.571-1.818v-1.5q0-2.5 2.5-2.5");
}

</style>
