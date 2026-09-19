<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xub-6lbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-e-mobiledata" /></template>
<style>
.xub-6lbnc {
  fill: currentColor;
  d: path("M16 9V7H8v10h8v-2h-6v-2h6v-2h-6V9z");
}

</style>
