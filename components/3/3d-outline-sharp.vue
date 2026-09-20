<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7_bxbcco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:3d-outline-sharp" /></template>
<style>
.r7_bxbcco {
  fill: currentColor;
  d: path("M13 9v6h4l1-1v-4l-1-1zm1.5 4.5v-3h2v3zm-8 1.5h4l.5-.5v-2l-.5-.5l.5-.5v-2l-.5-.5h-4v1.5h3v.75h-2v1.5h2v.75h-3zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
