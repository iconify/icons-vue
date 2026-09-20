<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1i_uabgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-box-outline-blank-sharp" /></template>
<style>
.y1i_uabgk {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5z");
}

</style>
