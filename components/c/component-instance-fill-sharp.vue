<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8j4vrn4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-instance-fill-sharp" /></template>
<style>
.m8j4vrn4r {
  fill: currentColor;
  d: path("M22.707 11.293a1 1 0 0 1 0 1.414l-10 10a1 1 0 0 1-1.414 0l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0Z");
}

</style>
