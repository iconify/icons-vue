<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypwnufbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-fill-sharp" /></template>
<style>
.ypwnufbgh {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Zm-4 3a1 1 0 0 0-1 1v2c0 1.087.283 2.142.969 3c.676.844 1.629 1.417 2.584 1.894a1 1 0 0 0 .894 0C14.546 18.845 15.999 17.581 16 15v-2a1 1 0 0 0-1-1Z");
}

</style>
