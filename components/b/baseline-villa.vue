<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv131p5kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-villa" /></template>
<style>
.nv131p5kb {
  fill: currentColor;
  d: path("M7 21H3V8l13-5v7H7zm12-11c-1.1 0-2 .9-2 2H9v9h5v-5h2v5h5v-9c0-1.1-.9-2-2-2");
}

</style>
