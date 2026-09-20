<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d0zcq54fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-left-12-filled" /></template>
<style>
.d0zcq54fq {
  fill: currentColor;
  d: path("M6.299 3.282C6.93 2.659 8 3.107 8 3.994v4.012c0 .887-1.07 1.335-1.701.713L4.26 6.713a1 1 0 0 1 0-1.425z");
}

</style>
