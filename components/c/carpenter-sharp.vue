<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehpkw1_-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carpenter-sharp" /></template>
<style>
.ehpkw1_-p {
  fill: currentColor;
  d: path("m14.075 22.7l-4.25-4.225l1.425-1.425L3.1 5.4L7 1.5l14.15 14.125zm0-2.825L18.3 15.65l-1.4-1.425l-4.25 4.25z");
}

</style>
