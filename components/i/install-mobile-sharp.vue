<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogxzxcc_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:install-mobile-sharp" /></template>
<style>
.ogxzxcc_g {
  fill: currentColor;
  d: path("M5 23V1h9v5H7v12h10v-2h2v7zm13-9l-5-5l1.4-1.4l2.6 2.6V3h2v7.2l2.6-2.6L23 9z");
}

</style>
