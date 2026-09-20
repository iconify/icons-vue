<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itc3kac9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:coffee-maker-sharp" /></template>
<style>
.itc3kac9j {
  fill: currentColor;
  d: path("M4 22V2h16v2h-2v3H8V4H6v16h4.05q-.95-.675-1.5-1.713T8 16v-5h10v5q0 1.25-.55 2.288T15.95 20H20v2zm9.713-12.288Q14 9.425 14 9t-.288-.712T13 8t-.712.288T12 9t.288.713T13 10t.713-.288");
}

</style>
