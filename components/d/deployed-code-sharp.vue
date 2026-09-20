<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5tl7sbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-sharp" /></template>
<style>
.d5tl7sbxa {
  fill: currentColor;
  d: path("m12 21.146l-8-4.598V7.452l8-4.598l8 4.598v9.096zm-.5-8.86v7.428l.23.132q.136.077.27.077t.27-.077l.23-.132v-7.427L19 8.523v-.242q0-.097-.048-.193t-.144-.153l-.383-.221L12 11.427L5.575 7.714l-.383.22q-.096.058-.144.155Q5 8.185 5 8.28v.242z");
}

</style>
