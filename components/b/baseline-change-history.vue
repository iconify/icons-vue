<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnp3t2qtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-change-history" /></template>
<style>
.hnp3t2qtv {
  fill: currentColor;
  d: path("M12 7.77L18.39 18H5.61zM12 4L2 20h20z");
}

</style>
