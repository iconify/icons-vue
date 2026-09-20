<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk42opb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-small-24-regular" /></template>
<style>
.jk42opb5j {
  fill: currentColor;
  d: path("M12 9.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M8 12a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>
