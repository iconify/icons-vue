<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf1qy-r3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-fix-normal-outline" /></template>
<style>
.sf1qy-r3i {
  fill: currentColor;
  d: path("m20 7l-.95-2.05L17 4l2.05-.95L20 1l.95 2.05L23 4l-2.05.95L20 7ZM5.1 21.7l-2.8-2.8q-.3-.3-.3-.725t.3-.725L13.45 6.3q.3-.3.725-.3t.725.3l2.8 2.8q.3.3.3.725t-.3.725L6.55 21.7q-.3.3-.725.3t-.725-.3Zm.7-2.1l7.2-7.2l-1.4-1.4l-7.2 7.2l1.4 1.4Z");
}

</style>
