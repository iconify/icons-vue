<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg0jumbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:comment-bubble-sharp" /></template>
<style>
.tg0jumbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6h4.5m-4.5 4.25h4.5m-4.5 9.5h18.5m-9-16h9v10H15.5l-3.25 2.75v-2.75h-2v-10z");
}

</style>
