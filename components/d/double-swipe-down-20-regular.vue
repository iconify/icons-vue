<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gnc60i6zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:double-swipe-down-20-regular" /></template>
<style>
.gnc60i6zd {
  fill: currentColor;
  d: path("M5.854 17.854a.5.5 0 0 1-.708 0l-3-3a.5.5 0 0 1 .708-.707L5 16.293V5.5a.5.5 0 0 1 1 0v10.793l2.146-2.146a.5.5 0 0 1 .708.707zm9 0a.5.5 0 0 1-.708 0l-3-3a.5.5 0 0 1 .708-.707L14 16.293V5.5a.5.5 0 0 1 1 0v10.793l2.146-2.146a.5.5 0 0 1 .708.707zM11 5.5a3.5 3.5 0 0 0 2 3.163V7.5a2.5 2.5 0 1 1 3 0v1.163A3.5 3.5 0 1 0 11 5.5M4 8.663a3.5 3.5 0 1 1 3 0V7.5a2.5 2.5 0 1 0-3 0z");
}

</style>
