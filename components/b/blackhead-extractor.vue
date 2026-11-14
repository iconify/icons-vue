<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7vij2f9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blackhead-extractor" /></template>
<style>
.x7vij2f9u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 7q0-1.76 1.245-3.005T17 2.75t3.005 1.245T21.25 7t-1.245 3.005T17 11.25q-1.373 0-2.432-.757l-1.599 1.599q.822 1.298-.477 2.597l-5.303 5.303q-1.59 1.591-3.181 0t0-3.181l5.303-5.303q1.299-1.299 2.597-.477l1.599-1.599Q12.75 8.373 12.75 7");
}

</style>
