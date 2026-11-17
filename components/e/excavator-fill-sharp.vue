<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzjhaqwot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:excavator-fill-sharp" /></template>
<style>
.uzjhaqwot {
  fill: currentColor;
  d: path("m12.882 10.467l2.182-5.818a1 1 0 0 1 1.643-.356l5 5A1 1 0 0 1 22 10v5a1 1 0 0 1-1 1h-2a1 1 0 0 1-.894-.553l-1-2a1 1 0 0 1 .954-1.445a1 1 0 0 1 .834.551L19.618 14H20v-3.586l-3.609-3.609L14 13.181v1.99A3.001 3.001 0 0 1 13 21H5a3 3 0 1 1 0-6V8a1 1 0 0 1 1-1h3c.265 0 .52.105.707.293ZM7 9v3h4.586l-3-3Zm-2 8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Z");
}

</style>
