<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0d7-tz4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-download-corner-fill" /></template>
<style>
.z0d7-tz4f {
  fill: currentColor;
  d: path("M13 12c-.411 0-.789.264-.939.647l-1.354-1.354a2.415 2.415 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1Zm2-2a2 2 0 1 0 .001-3.999A2 2 0 0 0 15 10m-5.707 2.707l2.414 2.414a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l6.414-6.414a.414.414 0 0 1 .586 0m8 9l-3-3a1 1 0 0 1 1.414-1.414L17 18.586V15a1 1 0 0 1 2 0v3.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

</style>
