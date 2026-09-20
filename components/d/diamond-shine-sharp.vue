<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko4yr-y0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:diamond-shine-sharp" /></template>
<style>
.ko4yr-y0j {
  fill: currentColor;
  d: path("M4.575 7L2.45 4.875l1.425-1.4L6 5.6zM11 5V2h2v3zm8.375 2L17.95 5.575l2.125-2.125L21.5 4.875zM12 22l-8.075-8h16.15zM8 7h8l4.1 5H3.9z");
}

</style>
