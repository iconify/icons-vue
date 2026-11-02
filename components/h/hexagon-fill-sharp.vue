<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjtv3ob-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-fill-sharp" /></template>
<style>
.vjtv3ob-e {
  fill: currentColor;
  d: path("M21 17a1 1 0 0 1-.553.894l-8 4a1 1 0 0 1-.894 0l-8-4A1 1 0 0 1 3 17V7c0-.379.214-.725.553-.894l8-4a1 1 0 0 1 .894 0l8 4A1 1 0 0 1 21 7Z");
}

</style>
