<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an9300bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-frame-share-outline-sharp" /></template>
<style>
.an9300bdj {
  fill: currentColor;
  d: path("M1 18V6h17.175l-2 2H3v8h8v2zm12-2v-5h6.175L17.6 9.4L19 8l4 4l-4 4l-1.425-1.425l1.6-1.575H15v3zm-2-1H4V9h11.175H11z");
}

</style>
