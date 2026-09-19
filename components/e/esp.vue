<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jfpl573yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:esp" /></template>
<style>
.jfpl573yr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.637 3.922l-5.506 9.47l5.888 2.244l-7.01 9.084l4.43 1.57l-10.374 13.682l4.318-11.888l-4.906-1.402l3.168-8.467l-6.337-3.084l3.65-12.012C9.522 5.391 2.5 13.865 2.5 24c0 11.874 9.626 21.5 21.5 21.5S45.5 35.874 45.5 24c0-9.18-5.765-16.995-13.863-20.078");
}

</style>
