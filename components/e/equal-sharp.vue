<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb6pouu4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:equal-sharp" /></template>
<style>
.qb6pouu4l {
  fill: currentColor;
  d: path("M4 17v-3h16v3zm0-7V7h16v3z");
}

</style>
