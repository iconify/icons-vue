<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtv2llbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-sharp" /></template>
<style>
.vtv2llbak {
  fill: currentColor;
  d: path("M3 19V5h12.635L21 12l-5.365 7z");
}

</style>
