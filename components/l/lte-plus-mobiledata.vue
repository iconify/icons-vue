<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl7jcfu7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lte-plus-mobiledata" /></template>
<style>
.wl7jcfu7c {
  fill: currentColor;
  d: path("M1 16V8h2v6h3v2zm6 0v-6H5V8h6v2H9v6zm5 0V8h5v2h-3v1h3v2h-3v1h3v2zm8-1v-2h-2v-2h2V9h2v2h2v2h-2v2z");
}

</style>
