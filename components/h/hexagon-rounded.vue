<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgg0o-brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hexagon-rounded" /></template>
<style>
.rgg0o-brg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.788 5.369l2.349 4.069q1.479 2.563 0 5.125l-2.35 4.068q-1.479 2.563-4.438 2.563H9.651q-2.959 0-4.439-2.563l-2.348-4.068Q1.384 12 2.863 9.438l2.349-4.069q1.48-2.563 4.439-2.563h4.698q2.959 0 4.439 2.563");
}

</style>
