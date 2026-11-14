<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjrhynb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:exposure-video" /></template>
<style>
.tjrhynb7w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 3.75H6q-1.76 0-3.005 1.245T1.75 8v4.5q0 1.76 1.245 3.005T6 16.75h6.147q.316-1.284 1.317-2.286Q14.929 13 17 13q.113 0 .223.004q.027-.246.027-.504v-.286l1.744.872q1.122.561 2.189-.099q1.067-.659 1.067-1.914V8.427q0-1.255-1.067-1.914q-1.067-.66-2.189-.099l-1.795.897q-.2-1.322-1.194-2.316Q14.76 3.75 13 3.75m4 10.5q-3.75 0-3.75 3.75T17 21.75T20.75 18T17 14.25M14.75 18q0-1.837 1.5-2.174v4.348q-1.5-.337-1.5-2.174m4.5 0q0 1.837-1.5 2.174v-4.348q1.5.337 1.5 2.174");
}

</style>
