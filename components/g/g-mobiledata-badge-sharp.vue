<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk3jgtb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:g-mobiledata-badge-sharp" /></template>
<style>
.bk3jgtb_w {
  fill: currentColor;
  d: path("M8.5 16.5h7v-5h-2.615v1H14.5v3h-5v-7h6v-1h-7zM4 20V4h16v16z");
}

</style>
