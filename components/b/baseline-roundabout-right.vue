<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqh1y0bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-roundabout-right" /></template>
<style>
.cqh1y0bzu {
  fill: currentColor;
  d: path("M13.92 8C13.44 5.16 10.97 3 8 3C4.69 3 2 5.69 2 9c0 2.97 2.16 5.44 5 5.92V21h2v-6.09c0-.98-.71-1.8-1.67-1.97a3.999 3.999 0 1 1 4.61-4.61c.17.96.99 1.67 1.97 1.67h4.26l-1.59 1.59L18 13l4-4l-4-4l-1.41 1.41L18.17 8z");
}

</style>
