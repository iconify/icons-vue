<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_q04abdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-delay-fill" /></template>
<style>
.w_q04abdz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.6569 6.3431C22.1035 7.7898 23 9.7911 23 12C23 16.4183 19.4183 20 15 20L5 20C2.7908 20 1 18.2092 1 16L1 8C1 5.7908 2.7908 4 5 4L15 4C17.2089 4 19.2102 4.8965 20.6569 6.3431Z");
}

</style>
