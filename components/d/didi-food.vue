<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df2t90b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:didi-food" /></template>
<style>
.df2t90b-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.17 15.92V8.588H4.5v11.323c0 10.752 8.748 19.5 19.5 19.5s19.5-8.748 19.5-19.5v-3.993zm-.001 3.991c0 6.71-5.46 12.17-12.17 12.17s-12.168-5.46-12.168-12.17V15.92H36.17z");
}

</style>
