<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wda_fxanw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-fill-accent-20-regular" /></template>
<style>
.wda_fxanw {
  fill: currentColor;
  d: path("M4.836 12.5H4A1.5 1.5 0 0 0 2.5 14v2A1.5 1.5 0 0 0 4 17.5h12a1.5 1.5 0 0 0 1.5-1.5v-2c0-.295-.085-.57-.232-.802c-.38.969-1.226 1.802-2.518 1.802c-1.597 0-2.512-1.273-2.71-2.5h-1.062l-.95.95a3 3 0 0 1-4.243 0z");
}

</style>
