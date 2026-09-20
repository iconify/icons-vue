<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_5r5om-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-button-l1-sharp" /></template>
<style>
.a_5r5om-d {
  fill: currentColor;
  d: path("M14.55 15.5h1.35v-7H15l-2.475 1.8l.725.975l1.3-.975zm-6.4 0h4.475v-1.25h-3.1V8.5H8.15zM22 4v12q0 1.65-1.175 2.825T18 20H6q-1.65 0-2.825-1.175T2 16V4z");
}

</style>
