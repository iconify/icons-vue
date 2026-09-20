<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdezp8z3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bucket-check-outline-sharp" /></template>
<style>
.pdezp8z3h {
  fill: currentColor;
  d: path("M5 21L3 7h3V3h12v4h3l-2 14zm1.725-2h10.55L18.7 9H5.3zm4.225-2l4.95-4.95l-1.425-1.4l-3.525 3.525l-1.425-1.425L8.1 14.175zM8 7h8V5H8zm4 7");
}

</style>
