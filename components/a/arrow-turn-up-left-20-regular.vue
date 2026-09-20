<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l061w5bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-up-left-20-regular" /></template>
<style>
.l061w5bxm {
  fill: currentColor;
  d: path("M8.854 3.146a.5.5 0 0 0-.708 0l-4 4a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708-.708L5.707 8H12a2 2 0 0 1 2 2v6.5a.5.5 0 0 0 1 0V10a3 3 0 0 0-3-3H5.707l3.147-3.146a.5.5 0 0 0 0-.708");
}

</style>
