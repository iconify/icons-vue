<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xn8j8l_kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-next-12-regular" /></template>
<style>
.xn8j8l_kz {
  fill: currentColor;
  d: path("M2.646 2.854a.5.5 0 1 1 .708-.708l3.5 3.5a.5.5 0 0 1 0 .708l-3.5 3.5a.5.5 0 0 1-.708-.708L5.793 6zM10 2.5a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0z");
}

</style>
