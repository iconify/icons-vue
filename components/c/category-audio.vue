<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu1v061kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-audio" /></template>
<style>
.uu1v061kg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 12.438V12q0-3.417 2.416-5.834T12 3.75t5.834 2.416Q20.25 8.583 20.25 12v.438q1.5.531 1.5 2.562v2q0 2.75-2.75 2.75T16.25 17v-2q0-2.622 2.5-2.744V12q0-2.796-1.977-4.773T12 5.25T7.227 7.227T5.25 12v.256q2.5.122 2.5 2.744v2q0 2.75-2.75 2.75T2.25 17v-2q0-2.031 1.5-2.562");
}

</style>
