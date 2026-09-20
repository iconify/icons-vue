<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hx1t73bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crop-32-light" /></template>
<style>
.hx1t73bqe {
  fill: currentColor;
  d: path("M8 2.5a.5.5 0 0 0-1 0V7H2.5a.5.5 0 0 0 0 1H7v12.5a4.5 4.5 0 0 0 4.5 4.5H24v4.5a.5.5 0 0 0 1 0V25h4.5a.5.5 0 0 0 0-1h-18A3.5 3.5 0 0 1 8 20.5zM20.5 8h-11V7h11a4.5 4.5 0 0 1 4.5 4.5v11h-1v-11A3.5 3.5 0 0 0 20.5 8");
}

</style>
