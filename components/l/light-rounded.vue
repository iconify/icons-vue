<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb-z2abiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:light-rounded" /></template>
<style>
.lb-z2abiq {
  fill: currentColor;
  d: path("M9.82 18.18q-.897-.896-.897-2.18H5q-.413 0-.706-.294T4 15q0-3.134 2.166-5.47T11.5 7.012V4.885q0-.213.144-.357t.357-.144t.356.144t.143.356v2.127q3.17.183 5.335 2.519T20 15q0 .413-.294.706T19 16h-3.923q0 1.285-.896 2.18T12 19.078t-2.18-.896M5 15h14q0-2.9-2.05-4.95T12 8t-4.95 2.05T5 15");
}

</style>
