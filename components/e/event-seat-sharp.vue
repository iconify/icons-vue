<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2z2vcbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-seat-sharp" /></template>
<style>
.g2z2vcbwf {
  fill: currentColor;
  d: path("M4 21v-6h16v6h-2v-4H6v4zm-1-7v-3h3v3zm4 0V3h10v11zm11 0v-3h3v3z");
}

</style>
