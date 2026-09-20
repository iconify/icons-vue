<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h112n5b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:javascript-outline-sharp" /></template>
<style>
.h112n5b1z {
  fill: currentColor;
  d: path("M6 15v-2.5h1.5v1H9V9h1.5v6zm6 0v-2h1.5v.5h2v-1H12V9h5v2h-1.5v-.5h-2v1H17V15z");
}

</style>
