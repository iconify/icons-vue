<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx2gamkmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carpenter-outline-sharp" /></template>
<style>
.zx2gamkmb {
  fill: currentColor;
  d: path("m14.075 22.7l-4.25-4.225l1.425-1.425L3.1 5.4L7 1.5l14.15 14.125zm-1.4-7.075l2.825-2.8l-8.5-8.5l-1.3 1.3zm1.4 4.25L18.3 15.65l-1.4-1.425l-4.25 4.25zm-1.4-4.25l2.825-2.8z");
}

</style>
