<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6vrtlb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:landscape" /></template>
<style>
.d6vrtlb_x {
  fill: currentColor;
  d: path("m2.904 17l4.192-5.616L10.558 16h2.544l-2.64-3.5l3.634-4.846l7 9.346z");
}

</style>
