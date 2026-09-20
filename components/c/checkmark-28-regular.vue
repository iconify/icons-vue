<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="tptj_qrbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-28-regular" /></template>
<style>
.tptj_qrbo {
  fill: currentColor;
  d: path("M4.03 13.47a.75.75 0 0 0-1.06 1.06l7 7a.75.75 0 0 0 1.06 0l14-14a.75.75 0 0 0-1.06-1.06L10.5 19.94z");
}

</style>
