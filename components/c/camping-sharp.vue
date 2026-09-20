<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd29l_tsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:camping-sharp" /></template>
<style>
.jd29l_tsz {
  fill: currentColor;
  d: path("M2 22v-4.65l8.75-11.8L9 3.2L10.6 2L12 3.875L13.4 2L15 3.2l-1.75 2.35L22 17.35V22zm6.225-2h7.55L12 14.725z");
}

</style>
