<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbsl7zjag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-fusiontable-sharp" /></template>
<style>
.mbsl7zjag {
  fill: currentColor;
  d: path("M4 20V4h16v16zM19 8.096l-5.78 6.454l-3.99-3.988L5 14.792v1.427l4.23-4.23L13.243 16L19 9.596z");
}

</style>
