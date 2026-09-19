<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtq2yxboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-label-off" /></template>
<style>
.qtq2yxboo {
  fill: currentColor;
  d: path("m3.25 2.75l17 17L19 21l-2-2H5c-1.1 0-2-.9-2-2V7c0-.55.23-1.05.59-1.41L2 4zM22 12l-4.37-6.16C17.27 5.33 16.67 5 16 5H8l11 11z");
}

</style>
