<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_0dfi6tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-2-outline-sharp" /></template>
<style>
.p_0dfi6tt {
  fill: currentColor;
  d: path("M11.5 20v-7.5H4v-1h7.5V4h1v7.5H20v1h-7.5V20z");
}

</style>
