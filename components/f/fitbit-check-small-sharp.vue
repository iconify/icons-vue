<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_ecxcb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitbit-check-small-sharp" /></template>
<style>
.m_ecxcb6a {
  fill: currentColor;
  d: path("m10.5 16.2l-4-4l1.4-1.4l2.6 2.6l5.6-5.6l1.4 1.4Z");
}

</style>
