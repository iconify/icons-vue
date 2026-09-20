<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep_njeuxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:castle" /></template>
<style>
.ep_njeuxy {
  fill: currentColor;
  d: path("M1 21V9h2v2h2V3h2v2h2V3h2v2h2V3h2v2h2V3h2v8h2V9h2v12h-9v-3q0-.825-.587-1.412T12 16t-1.412.588T10 18v3zm8-9h2V9H9zm4 0h2V9h-2z");
}

</style>
