<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ospkjfbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-align-center-outline-sharp" /></template>
<style>
.ospkjfbda {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm4-4v-2h10v2zm-4-4v-2h18v2zm4-4V7h10v2zM3 5V3h18v2z");
}

</style>
