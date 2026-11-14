<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4y-t1bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:highlighter-off" /></template>
<style>
.q4y-t1bga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.859 7.898l4.737-4.737l4.243 4.243l-4.738 4.737m-4.387 3.538l-1.128.564l-2.829-2.829l.554-1.107m-.2 1.461l2.121 2.121l-1.06 1.061l-3.182-1.061ZM3.5 3.5l17 17");
}

</style>
