<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x99jzkbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-aspect-ratio-sharp" /></template>
<style>
.x99jzkbnp {
  fill: currentColor;
  d: path("M6.192 12h1.616v-1.616H6.192zM10 12h1.616v-1.616H10zm3.808 3.808h1.615v-1.616h-1.615zm0-3.808h1.615v-1.616h-1.615zM3 19V5h18v14z");
}

</style>
