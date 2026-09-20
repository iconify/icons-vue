<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my8z-jbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-open-outline-sharp" /></template>
<style>
.my8z-jbha {
  fill: currentColor;
  d: path("M5 21V3h9.5L19 7.5v7h-1V8h-4V4H6v16h9.5v1zm16.95.664l-3.45-3.45v2.955h-1V16.5h4.67v1h-2.982l3.45 3.45zM6 20V4z");
}

</style>
