<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpue41bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-48-regular" /></template>
<style>
.tpue41bkq {
  fill: currentColor;
  d: path("M22.25 6a1.25 1.25 0 1 0 0 2.5h15.482L6.366 39.866a1.25 1.25 0 0 0 1.768 1.768L39.5 10.268V25.75a1.25 1.25 0 1 0 2.5 0V7.25C42 6.56 41.44 6 40.75 6z");
}

</style>
