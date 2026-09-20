<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hhmc_o5fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-next-16-regular" /></template>
<style>
.hhmc_o5fe {
  fill: currentColor;
  d: path("M3.646 3.854a.5.5 0 1 1 .708-.708l4.5 4.5a.5.5 0 0 1 0 .708l-4.5 4.5a.5.5 0 0 1-.708-.708L7.793 8zM12 3.5a.5.5 0 0 0-1 0v9a.5.5 0 0 0 1 0z");
}

</style>
