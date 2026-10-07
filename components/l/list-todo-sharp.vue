<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqe7kf98w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-todo-sharp" /></template>
<style>
.wqe7kf98w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L8 4L8 10L2 10L2 4ZM1.7071 17.7071L4 20L8.2929 15.7071M11 7L23 7M11 18L23 18");
}

</style>
