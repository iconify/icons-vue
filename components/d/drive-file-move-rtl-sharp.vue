<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syd_ombeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-file-move-rtl-sharp" /></template>
<style>
.syd_ombeb {
  fill: currentColor;
  d: path("m12.025 17.025l1.4-1.4L11.8 14H16v-2h-4.2l1.625-1.625l-1.4-1.4L8 13ZM2 20V4h8l2 2h10v14Z");
}

</style>
