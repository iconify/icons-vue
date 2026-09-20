<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkbpaqb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:article-sharp" /></template>
<style>
.rkbpaqb2o {
  fill: currentColor;
  d: path("M7 17h7v-2H7zm0-4h10v-2H7zm0-4h10V7H7zM3 21V3h18v18z");
}

</style>
