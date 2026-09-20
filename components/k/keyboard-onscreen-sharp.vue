<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agteejbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-onscreen-sharp" /></template>
<style>
.agteejbpd {
  fill: currentColor;
  d: path("M8.23 16.77h7.54v-1.54H8.23zm-3-3h1.54v-1.54H5.23zm3 0h1.54v-1.54H8.23zm3 0h1.54v-1.54h-1.54zm3 0h1.54v-1.54h-1.54zm3 0h1.54v-1.54h-1.54zM3 19V5h18v14zm1-9.5h16V6H4z");
}

</style>
