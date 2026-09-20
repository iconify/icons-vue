<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzsfkwb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contrast-square-sharp" /></template>
<style>
.lzsfkwb-u {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5zm1.289-9.827h2v2h.884v-2h2v-.885h-2v-2h-.885v2h-2zm10.698 6.423h-4.385v-.884h4.385z");
}

</style>
