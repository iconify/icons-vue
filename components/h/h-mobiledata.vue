<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wff0krbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:h-mobiledata" /></template>
<style>
.wff0krbrj {
  fill: currentColor;
  d: path("M7 17V7h2v4h6V7h2v10h-2v-4H9v4z");
}

</style>
