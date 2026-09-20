<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syb2ea1hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:eject-outline-sharp" /></template>
<style>
.syb2ea1hm {
  fill: currentColor;
  d: path("M5 19v-2h14v2zm.35-4L12 5l6.65 10zm3.7-2h5.9L12 8.6z");
}

</style>
