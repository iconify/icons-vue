<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfvbckbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-off-fill-round" /></template>
<style>
.hfvbckbkn {
  fill: currentColor;
  d: path("M19.951 17.708L5.588 3.345A4.97 4.97 0 0 1 9 2h4c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v8q0 .356-.049.708M2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414l-1.535-1.535A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7.414L1.293 4.707a.999.999 0 1 1 1.414-1.414M13 7a2 2 0 0 0 2 2h3l-5-5Z");
}

</style>
