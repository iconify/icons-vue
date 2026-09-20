<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txjnktd0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brightness-auto" /></template>
<style>
.txjnktd0v {
  fill: currentColor;
  d: path("M8.185 16h.946l1.03-2.608h3.727L14.92 16h.973L12.34 7h-.64zm2.273-3.408l1.492-4.019h.1l1.53 4.02zM12 21.916L9.073 19H5v-4.073L2.085 12L5 9.073V5h4.073L12 2.085L14.927 5H19v4.073L21.916 12L19 14.927V19h-4.073z");
}

</style>
