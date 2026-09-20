<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-e53b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:download-2-outline-sharp" /></template>
<style>
.fq-e53b_y {
  fill: currentColor;
  d: path("M4 22v-2h16v2zm8-4L5 9h4V2h6v7h4zm0-3.25L14.9 11H13V4h-2v7H9.1zM12 11");
}

</style>
