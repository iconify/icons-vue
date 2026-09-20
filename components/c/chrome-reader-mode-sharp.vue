<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckrbk0gmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-reader-mode-sharp" /></template>
<style>
.ckrbk0gmo {
  fill: currentColor;
  d: path("M2 20V4h20v16zm11-2h7V6h-7zm1-8h5V8.5h-5zm0 2.5h5V11h-5zm0 2.5h5v-1.5h-5z");
}

</style>
