<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsua6gmxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-call-received" /></template>
<style>
.rsua6gmxm {
  fill: currentColor;
  d: path("M20 5.41L18.59 4L7 15.59V9H5v10h10v-2H8.41z");
}

</style>
