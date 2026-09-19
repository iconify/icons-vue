<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ujzbi0bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:droplet" /></template>
<style>
.ujzbi0bos {
  fill: currentColor;
  d: path("M31.993 2C20.563 17.624 14 32.007 14 43.827C14 53.859 22.064 62 32.001 62C41.946 62 50 53.859 50 43.827C50 32.007 43.245 17.383 31.993 2");
}

</style>
