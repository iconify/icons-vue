<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aw8q1b6_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-button-b-20-regular" /></template>
<style>
.aw8q1b6_f {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 1a7 7 0 1 0 0 14a7 7 0 0 0 0-14m.25 3a2.25 2.25 0 0 1 1.625 3.803A2.248 2.248 0 0 1 10.75 14H8.5a.5.5 0 0 1-.5-.5v-7a.5.5 0 0 1 .5-.5zM9 13h1.75a1.25 1.25 0 1 0 0-2.5H9zm0-3.5h1.25a1.25 1.25 0 1 0 0-2.5H9z");
}

</style>
