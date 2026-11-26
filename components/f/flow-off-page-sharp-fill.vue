<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj693ccpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-off-page-sharp-fill" /></template>
<style>
.zj693ccpl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4L22 4C22.5523 4 23 4.4477 23 5L23 12C23 12.3264 22.8407 12.6322 22.5733 12.8193L12.5733 19.8168C12.4053 19.9344 12.2051 19.9975 12 19.9975C11.7949 19.9975 11.5947 19.9344 11.4267 19.8168L1.4267 12.8193C1.1593 12.6322 1 12.3264 1 12L1 5C1 4.4477 1.4477 4 2 4Z");
}

</style>
