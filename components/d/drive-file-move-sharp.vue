<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emliohbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-file-move-sharp" /></template>
<style>
.emliohbmh {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm10.392-5.5l-1.913 1.914l.708.707L15.307 13l-3.12-3.121l-.708.708l1.913 1.913h-4.7v1z");
}

</style>
