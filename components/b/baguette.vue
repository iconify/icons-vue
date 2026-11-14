<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv98zmbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baguette" /></template>
<style>
.fv98zmbfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.282 14.828l9.546-9.546a2.75 2.75 0 0 1 3.89 0a2.75 2.75 0 0 1 0 3.89l-9.546 9.546a2.75 2.75 0 0 1-3.89 0a2.75 2.75 0 0 1 0-3.89m.884-.883l5.304 2.474m-2.122-5.656l5.304 2.474M12.53 7.581l5.304 2.474");
}

</style>
