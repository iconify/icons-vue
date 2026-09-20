<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfgvdj6iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:diamond-outline-sharp" /></template>
<style>
.nfgvdj6iu {
  fill: currentColor;
  d: path("M12 21L2 9l3-6h14l3 6zM9.625 8h4.75l-1.5-3h-1.75zM11 16.675V10H5.45zm2 0L18.55 10H13zM16.6 8h2.65l-1.5-3H15.1zM4.75 8H7.4l1.5-3H6.25z");
}

</style>
