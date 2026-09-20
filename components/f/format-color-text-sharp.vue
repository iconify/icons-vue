<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sisfprb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-color-text-sharp" /></template>
<style>
.sisfprb3n {
  fill: currentColor;
  d: path("M2 24v-4h20v4zm3.5-7l5.25-14h2.5l5.25 14h-2.4l-1.25-3.6H9.2L7.9 17zm4.4-5.6h4.2l-2.05-5.8h-.1z");
}

</style>
