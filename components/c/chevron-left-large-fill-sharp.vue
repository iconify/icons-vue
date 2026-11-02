<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3-7w_6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-left-large-fill-sharp" /></template>
<style>
.hr3-7w_6u {
  fill: currentColor;
  d: path("m10.414 12l5.293 5.293a.999.999 0 1 1-1.414 1.414l-6-6a1 1 0 0 1 0-1.414l6-6a.999.999 0 1 1 1.414 1.414Z");
}

</style>
