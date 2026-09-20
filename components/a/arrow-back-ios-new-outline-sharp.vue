<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw4pcbblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-back-ios-new-outline-sharp" /></template>
<style>
.zw4pcbblw {
  fill: currentColor;
  d: path("M16 22L6 12L16 2l1.775 1.775L9.55 12l8.225 8.225z");
}

</style>
