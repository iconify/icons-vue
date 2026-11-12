<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b30z05z7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-close-corner-fill" /></template>
<style>
.b30z05z7d {
  fill: currentColor;
  d: path("M13 12c-.411 0-.789.264-.939.647l-1.354-1.354a2.415 2.415 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1Zm.158-4.779a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558m-3.865 5.486l2.414 2.414a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l6.414-6.414a.414.414 0 0 1 .586 0m7.414 2.586L18 16.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L19.414 18l1.293 1.293a.999.999 0 1 1-1.414 1.414L18 19.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L16.586 18l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
