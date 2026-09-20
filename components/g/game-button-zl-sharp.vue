<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riz7dacmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-button-zl-sharp" /></template>
<style>
.riz7dacmy {
  fill: currentColor;
  d: path("M6.425 15.5h5.15v-1.25h-3.4l3.325-4.7V8.5H6.575v1.25H9.75L6.425 14.5zM22 4v12q0 1.675-1.175 2.838T18 20H6q-1.675 0-2.838-1.162T2 16V4zm-8.95 11.5h4.45v-1.25h-3.1V8.5h-1.35z");
}

</style>
