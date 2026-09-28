<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy8roybus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lifebuoy-sharp-fill" /></template>
<style>
.zy8roybus {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12ZM15.2426 12C15.2426 10.2091 13.7908 8.7574 12 8.7574C10.2091 8.7574 8.7574 10.2091 8.7574 12C8.7574 13.7908 10.2091 15.2426 12 15.2426C13.7909 15.2426 15.2426 13.7909 15.2426 12ZM16.4142 15L15 16.4142L17.6569 19.0711L19.0711 17.6569L16.4142 15ZM9 16.4142L7.5858 15L4.9289 17.6569L6.3431 19.0711L9 16.4142ZM7.5858 9L9 7.5858L6.3431 4.9289L4.9289 6.3431L7.5858 9ZM15 7.5858L16.4142 9L19.0711 6.3431L17.6569 4.9289L15 7.5858Z");
}

</style>
