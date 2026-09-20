<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rv0xaobis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-checkmark-12-regular" /></template>
<style>
.rv0xaobis {
  fill: currentColor;
  d: path("M8.354 3.396a.5.5 0 0 1 0 .708l-2.5 2.5a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L5.5 5.543l2.146-2.147a.5.5 0 0 1 .708 0M10.5 5a4.5 4.5 0 0 0-9 0c0 1.863 1.42 3.815 4.2 5.9a.5.5 0 0 0 .6 0c2.78-2.085 4.2-4.037 4.2-5.9m-8 0a3.5 3.5 0 1 1 7 0c0 1.355-1.059 2.918-3.224 4.653L6 9.871l-.276-.218C3.559 7.918 2.5 6.355 2.5 5");
}

</style>
