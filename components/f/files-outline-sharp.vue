<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiszrwonm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:files-outline-sharp" /></template>
<style>
.eiszrwonm {
  fill: currentColor;
  d: path("M3 19V7h6.942l2-2H21v14zm2.114-5.77h6.117V7.115zM4 12.943L8.942 8H4zm0 1.289V18h16V6h-7.77v8.23zm7.5-2.731");
}

</style>
