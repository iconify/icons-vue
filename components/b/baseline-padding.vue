<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmaeey4yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-padding" /></template>
<style>
.mmaeey4yo {
  fill: currentColor;
  d: path("M3 3v18h18V3zm16 16H5V5h14zM11 7h2v2h-2zM7 7h2v2H7zm8 0h2v2h-2z");
}

</style>
