<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw01rbcga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-fold-sharp" /></template>
<style>
.pw01rbcga {
  fill: currentColor;
  d: path("M10.385 20V3.821l5.884-2.627V4H21v16zm1.752-1H20V5h-3.73v12.16zM3 5.23V4h1.23v1.23zM3 20v-1.23h1.23V20zm0-3.692v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zm3.692-3.692V4h1.231v1.23zm0 14.769v-1.23h1.231V20z");
}

</style>
