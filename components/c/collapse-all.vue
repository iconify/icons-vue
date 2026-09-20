<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjmjzm8wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collapse-all" /></template>
<style>
.sjmjzm8wg {
  fill: currentColor;
  d: path("M7.4 22L6 20.6l6-6l6 6l-1.4 1.4l-4.6-4.6zM12 9.4l-6-6L7.4 2L12 6.6L16.6 2L18 3.4z");
}

</style>
