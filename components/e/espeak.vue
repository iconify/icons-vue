<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="loz7itdwq"/><path class="y9bzupbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:espeak" /></template>
<style>
.loz7itdwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 25.569c6.942-3.787 14.28-15.857 14.28-15.857c1.498 4.812 5.6 7.1 9.23-1.894c1.42 2.762 9.467 13.175 13.49 15.621c-10.098 1.736-10.472 15.966-20.117 16.725c-7.022.552-5.286-11.992-16.883-14.595");
}

.y9bzupbxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.914 23.518c4.97-1.262 6.627-4.497 8.914-4.734s4.852 2.09 8.008 2.367c-4.655 8.994-9.388 15.344-16.922 2.367");
}

</style>
