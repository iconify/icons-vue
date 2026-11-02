<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr3_-mb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-medium-fill-sharp" /></template>
<style>
.yr3_-mb_s {
  fill: currentColor;
  d: path("M5.551 9.275a7 7 0 0 1 9.173-3.723a7 7 0 0 1 3.724 9.172A7 7 0 0 1 5.551 9.275");
}

</style>
