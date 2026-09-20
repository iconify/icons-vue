<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osw3g-k7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-color-sharp" /></template>
<style>
.osw3g-k7q {
  fill: currentColor;
  d: path("M2 24v-4h20v4zm2-6v-4.25l12.625-12.6l4.2 4.275L8.25 18zM16.6 6.8L18 5.4L16.6 4l-1.4 1.4z");
}

</style>
