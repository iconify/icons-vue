<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="powor1xqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:briefcase-fill-round" /></template>
<style>
.powor1xqb {
  fill: currentColor;
  d: path("M7.099 7a5.003 5.003 0 0 1 9.802 0H17a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5ZM9.17 7h5.66a3.002 3.002 0 0 0-5.66 0");
}

</style>
