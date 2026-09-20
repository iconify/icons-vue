<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ipr0skc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-ink-highlighter-outline-sharp" /></template>
<style>
.m4ipr0skc {
  fill: currentColor;
  d: path("M2 24v-4h20v4zm12.6-12l-1.3-1.3L12 9.4l-4 4l2.575 2.6zm-1.175-4l1.3 1.275l1.275 1.3L20 6.6L17.4 4zM3.5 18l3.15-3.15l-.75-.725V12.7l5.425-5.425l5.4 5.4L11.3 18.1H9.9l-.75-.75l-.65.65zm7.825-10.725l6.1-6.1L22.85 6.6l-6.125 6.075z");
}

</style>
