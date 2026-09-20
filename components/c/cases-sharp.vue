<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3v0vab3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cases-sharp" /></template>
<style>
.s3v0vab3f {
  fill: currentColor;
  d: path("M2 20.192V9.423h1v9.77h15.5v1zm3-3v-11h5.308V3h6.384v3.192H22v11zm6.308-11h4.384V4h-4.384z");
}

</style>
