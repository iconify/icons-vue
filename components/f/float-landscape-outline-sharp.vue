<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi-tg0bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-landscape-outline-sharp" /></template>
<style>
.vi-tg0bdw {
  fill: currentColor;
  d: path("M2 20V4h20v7h-2V6H4v12h11v2Zm15 0v-7h5v7Zm-5-8Z");
}

</style>
