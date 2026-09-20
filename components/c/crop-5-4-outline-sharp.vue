<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhxqfj7vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-5-4-outline-sharp" /></template>
<style>
.hhxqfj7vc {
  fill: currentColor;
  d: path("M4 19V5h16v14zm1-1h14V6H5zm0 0V6z");
}

</style>
