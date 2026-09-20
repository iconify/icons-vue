<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0nyvcowu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-arrow-outline-rounded" /></template>
<style>
.x0nyvcowu {
  fill: currentColor;
  d: path("m11.475 18.025l-8.15-5.175q-.475-.3-.475-.85t.475-.85l8.15-5.175q.5-.325 1.013-.037t.512.887V11h8q.425 0 .713.288T22 12t-.288.713T21 13h-8v4.175q0 .6-.513.888t-1.012-.038M11 15.35v-6.7L5.725 12zM11 12");
}

</style>
