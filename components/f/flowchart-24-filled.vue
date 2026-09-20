<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el2vi-j6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flowchart-24-filled" /></template>
<style>
.el2vi-j6z {
  fill: currentColor;
  d: path("M2.998 5.246a2.25 2.25 0 0 1 2.25-2.25h2.507a2.25 2.25 0 0 1 2.25 2.25v2.507a2.25 2.25 0 0 1-2.25 2.25H7.25v3.707q.07.051.134.116l2.79 2.79q.065.065.117.135h3.714v-.5a2.25 2.25 0 0 1 2.25-2.25h2.494a2.25 2.25 0 0 1 2.25 2.25v2.504a2.25 2.25 0 0 1-2.25 2.25h-2.494a2.25 2.25 0 0 1-2.25-2.25v-.504H10.29a1 1 0 0 1-.115.133l-2.791 2.792a1.25 1.25 0 0 1-1.768 0l-2.792-2.791a1.25 1.25 0 0 1 0-1.768l2.792-2.792a1 1 0 0 1 .134-.116v-3.706h-.502a2.25 2.25 0 0 1-2.25-2.25z");
}

</style>
