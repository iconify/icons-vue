<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkzcl4u6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cards-stack-sharp" /></template>
<style>
.qkzcl4u6u {
  fill: currentColor;
  d: path("M10.308 8.5h7v-1h-7zm0 3.154h4v-1h-4zm-6.044 8.5L2.73 9.119l1.5-.167v8.606h14.775l.057.715zm2.351-4.958V4H21v11.196z");
}

</style>
