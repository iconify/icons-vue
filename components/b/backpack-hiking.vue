<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz1h2rnfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:backpack-hiking" /></template>
<style>
.pz1h2rnfj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 8v7.25H4q-2.25 0-2.25 3.25T4 21.75h14.5q1.346 0 2.298-.952t.952-2.298q0-3.25-3.25-3.25h-.25V8q0-5.75-6.25-5.75T5.75 8m10 12.25v-3.5h2.75q1.75 0 1.75 1.75q0 .725-.513 1.237q-.512.513-1.237.513zm-1.5-3.5v3.5h-4.5v-3.5zm.75-1.5H7.25V9.539q4.75 1.425 9.5 0v5.711zM7.25 7.966Q7.269 3.75 12 3.75t4.75 4.216q-4.75 1.565-9.5 0M6.019 20.25q.231-.708.231-1.75t-.231-1.75H8.25v3.5z");
}

</style>
