<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8485rbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-read-pause-sharp" /></template>
<style>
.t8485rbzw {
  fill: currentColor;
  d: path("M9.808 13.5h1v-7h-1zm3.384 0h1v-7h-1zM3 20.077V3h18v14H6.077z");
}

</style>
