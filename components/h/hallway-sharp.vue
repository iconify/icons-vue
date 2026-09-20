<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmlgg6klm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hallway-sharp" /></template>
<style>
.wmlgg6klm {
  fill: currentColor;
  d: path("M3 22V4h5l4-4l4 4h5v18zm3-4h12l-3.75-5l-3 4L9 14zm4.1-14h3.8L12 2.1z");
}

</style>
