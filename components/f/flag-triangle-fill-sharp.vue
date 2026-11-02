<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwiwjnbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-fill-sharp" /></template>
<style>
.cwiwjnbbn {
  fill: currentColor;
  d: path("M18.447 8.106a.998.998 0 0 1 0 1.788L7 15.618V21a1 1 0 0 1-2 0V3a1 1 0 0 1 1.447-.894Z");
}

</style>
