<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfqgtltdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:last-page-outline-sharp" /></template>
<style>
.rfqgtltdl {
  fill: currentColor;
  d: path("m7 18l-1.4-1.4l4.6-4.6l-4.6-4.6L7 6l6 6zm9 0V6h2v12z");
}

</style>
