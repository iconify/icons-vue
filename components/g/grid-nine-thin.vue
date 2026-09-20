<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tm6eh8fhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:grid-nine-thin" /></template>
<style>
.tm6eh8fhw {
  fill: currentColor;
  d: path("M216 52H40a12 12 0 0 0-12 12v128a12 12 0 0 0 12 12h176a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12m-116 96v-40h56v40Zm56 8v40h-56v-40ZM36 108h56v40H36Zm64-8V60h56v40Zm64 8h56v40h-56Zm56-44v36h-56V60h52a4 4 0 0 1 4 4M40 60h52v40H36V64a4 4 0 0 1 4-4m-4 132v-36h56v40H40a4 4 0 0 1-4-4m180 4h-52v-40h56v36a4 4 0 0 1-4 4");
}

</style>
