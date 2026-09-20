<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3jx5cccl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-add-sharp" /></template>
<style>
.i3jx5cccl {
  fill: currentColor;
  d: path("M17 9V7h-2V5h2V3h2v2h2v2h-2v2zM5 21V3h9q-.5.75-.75 1.438T13 6q0 1.8 1.138 3.175T17 10.9q.575.075 1 .075t1-.075V21l-7-3z");
}

</style>
