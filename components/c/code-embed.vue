<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwwub_b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:code-embed" /></template>
<style>
.cwwub_b-p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 1.75h6q1.76 0 3.005 1.245T16.75 6v9.5q0 1.76-1.245 3.005T12.5 19.75h-6q-1.76 0-3.005-1.245T2.25 15.5V6q0-1.76 1.245-3.005T6.5 1.75");
}

</style>
