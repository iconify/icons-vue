<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo8djbh0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-break-right-outline" /></template>
<style>
.zo8djbh0d {
  fill: currentColor;
  d: path("M3 5V3h18v2zm8 12V7h10v10zm2-2h6V9h-6zM3 21v-2h18v2zm13-9");
}

</style>
