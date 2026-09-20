<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on0ycjvjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-h1-outline-sharp" /></template>
<style>
.on0ycjvjn {
  fill: currentColor;
  d: path("M5 17V7h2v4h4V7h2v10h-2v-4H7v4zm12 0V9h-2V7h4v10z");
}

</style>
