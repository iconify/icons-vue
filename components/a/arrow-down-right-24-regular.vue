<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1wt4h5yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-right-24-regular" /></template>
<style>
.l1wt4h5yx {
  fill: currentColor;
  d: path("M10.75 21.005a.75.75 0 1 1 0-1.5h7.67l-15.2-15.2a.765.765 0 1 1 1.081-1.081l15.2 15.2v-7.67a.75.75 0 0 1 1.5 0v9.5a.75.75 0 0 1-.75.75z");
}

</style>
