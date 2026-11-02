<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgvuc9pkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-slash-fill" /></template>
<style>
.fgvuc9pkq {
  fill: currentColor;
  d: path("m6.382 4.968l-.711-.712a10.001 10.001 0 0 1 14.073 14.073Zm-2.126.703l14.073 14.073A10.001 10.001 0 0 1 4.256 5.671");
}

</style>
