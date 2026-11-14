<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfigpmbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:join-left" /></template>
<style>
.sfigpmbfw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.25 12q0-2.796 1.977-4.773T8 5.25q2.27 0 4 1.303q1.73-1.303 4-1.303q2.796 0 4.773 1.977T22.75 12t-1.977 4.773T16 18.75q-2.27 0-4-1.303q-1.73 1.303-4 1.303q-2.796 0-4.773-1.977T1.25 12m2-2.5q0 1.75 1.75 1.75T6.75 9.5T5 7.75T3.25 9.5m7 2.5q0-1.75 1.75-1.75T13.75 12T12 13.75T10.25 12M5 12.75q-1.75 0-1.75 1.75T5 16.25t1.75-1.75T5 12.75");
}

</style>
