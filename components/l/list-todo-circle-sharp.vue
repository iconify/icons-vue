<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuh_dfm5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-todo-circle-sharp" /></template>
<style>
.yuh_dfm5f {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7C8 8.6569 6.6569 10 5 10C3.3431 10 2 8.6569 2 7C2 5.3431 3.3431 4 5 4C6.6569 4 8 5.3431 8 7ZM8 17C8 18.6569 6.6569 20 5 20C3.3431 20 2 18.6569 2 17C2 15.3431 3.3431 14 5 14C6.6569 14 8 15.3431 8 17ZM11 7L23 7M11 17L23 17");
}

</style>
