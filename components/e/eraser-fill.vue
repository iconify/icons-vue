<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu-ekjb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-fill" /></template>
<style>
.fu-ekjb_h {
  fill: currentColor;
  d: path("m9 8.586l4.293-4.293a2.414 2.414 0 0 1 3.414 0l4 4a2.414 2.414 0 0 1 0 3.414L16.414 16Zm-5.707 9.121a2.414 2.414 0 0 1 0-3.414L7.586 10L15 17.414L13.414 19H21a1 1 0 0 1 0 2H7a1 1 0 0 1-.707-.293Z");
}

</style>
