<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lckuwvg-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:file-upload" /></template>
<style>
.lckuwvg-j {
  fill: currentColor;
  d: path("M9 16h6v-6h4l-7-7l-7 7h4zm-4 2h14v2H5z");
}

</style>
