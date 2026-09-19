<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oifwthb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-arrow-left" /></template>
<style>
.oifwthb4m {
  fill: currentColor;
  d: path("m14 7l-5 5l5 5z");
}

</style>
