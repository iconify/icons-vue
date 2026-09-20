<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pucpw0bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-share-sharp" /></template>
<style>
.pucpw0bwj {
  fill: currentColor;
  d: path("M1 18V6h17.175l-3 3H11v9zm12-2v-5h6.175L17.6 9.4L19 8l4 4l-4 4l-1.425-1.425l1.6-1.575H15v3z");
}

</style>
