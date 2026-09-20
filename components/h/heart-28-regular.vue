<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sbq-p9b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-28-regular" /></template>
<style>
.sbq-p9b3u {
  fill: currentColor;
  d: path("M14.604 6.193a6.519 6.519 0 1 1 9.509 8.913l-9.58 9.672a.75.75 0 0 1-1.066 0l-9.58-9.672a6.52 6.52 0 0 1-.263-8.892c2.588-2.943 7.17-2.953 9.772-.021l.604.68zm8.646 1.011a5.02 5.02 0 0 0-7.524-.016L14.56 8.501a.75.75 0 0 1-1.122 0l-1.165-1.313a5.02 5.02 0 1 0-7.321 6.863L14 23.185l9.047-9.134a5.02 5.02 0 0 0 .203-6.847");
}

</style>
