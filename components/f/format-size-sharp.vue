<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr_651qfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-size-sharp" /></template>
<style>
.tr_651qfv {
  fill: currentColor;
  d: path("M14.827 19V6.25H9.904V5H21v1.25h-4.923V19zm-8.865 0v-7.846H3v-1.25h7.154v1.25H7.192V19z");
}

</style>
