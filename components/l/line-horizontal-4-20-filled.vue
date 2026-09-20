<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k91rbrbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-20-filled" /></template>
<style>
.k91rbrbar {
  fill: currentColor;
  d: path("M2 3.75A.75.75 0 0 1 2.75 3h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 3.75m0 4A.75.75 0 0 1 2.75 7h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 7.75M2.75 11a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5zM2 15.75a.75.75 0 0 1 .75-.75h14.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75");
}

</style>
