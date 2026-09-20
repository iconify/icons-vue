<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es2s7mbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-not-supported-sharp" /></template>
<style>
.es2s7mbhu {
  fill: currentColor;
  d: path("M20.11 21.53L18.579 20H4V5.421L2.47 3.885l.707-.708l17.646 17.646l-.713.708ZM7 16.5h8.079l-2.556-2.537l-1.138 1.512L9.5 13.192L7 16.5Zm13 .675L6.825 4H20v13.175Z");
}

</style>
