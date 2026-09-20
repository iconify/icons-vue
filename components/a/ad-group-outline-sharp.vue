<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0wr-cbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ad-group-outline-sharp" /></template>
<style>
.m0wr-cbne {
  fill: currentColor;
  d: path("M8 16h12V6H8zm-2 2V2h16v16zm-4 4V6h2v14h14v2zm6-6V4z");
}

</style>
