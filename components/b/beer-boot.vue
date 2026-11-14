<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmy3rwnuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beer-boot" /></template>
<style>
.xmy3rwnuu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.838 7.853q-.911-1.707.269-3.242q.998-1.297 2.5-1.181q.901-1.34 2.643-1.34q1.738 0 2.639 1.334q1.545-.135 2.443 1.324q1.057 1.719-.266 3.244q-.129.149-.316.215v5.302l3.545 1.552q2.955 1.266 2.955 4.189v2.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V8.207q-.132-.047-.239-.138t-.173-.216M5.75 11.25v9.5h13v-1.5q0-1.934-2.045-2.811l-4.006-1.752q-.1-.044-.183-.114q-.084-.071-.144-.162t-.091-.197T12.25 14v-2.75zm6.5-1.5v-1.5h-6.5v1.5z");
}

</style>
