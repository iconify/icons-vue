<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9t77fe1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-functions" /></template>
<style>
.r9t77fe1k {
  fill: currentColor;
  d: path("M18 4H6v2l6.5 6L6 18v2h12v-3h-7l5-5l-5-5h7z");
}

</style>
