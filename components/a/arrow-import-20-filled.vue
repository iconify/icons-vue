<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yj50wbcuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-import-20-filled" /></template>
<style>
.yj50wbcuq {
  fill: currentColor;
  d: path("M17.25 3.75a.75.75 0 0 1 .75.75v11a.75.75 0 0 1-1.5 0v-11a.75.75 0 0 1 .75-.75M2 10a.75.75 0 0 1 .75-.75h10.19l-2.72-2.72a.75.75 0 1 1 1.06-1.06l3.997 3.996a.8.8 0 0 1 .156.223a.75.75 0 0 1-.156.845L11.28 14.53a.75.75 0 1 1-1.06-1.06l2.72-2.72H2.75A.75.75 0 0 1 2 10");
}

</style>
