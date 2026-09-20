<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z16i-yb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:barcode-reader-sharp" /></template>
<style>
.z16i-yb5e {
  fill: currentColor;
  d: path("M6 21q-1.5 0-2.387-1.162T3.1 17.25l1.8-6.8q-.825-.525-1.362-1.425T3 7q0-1.65 1.175-2.825T7 3h11.225l-4 8h-3.25l-.275 1H12v4H9.65l-.75 2.8q-.275.975-1.075 1.588T6 21M19 5l-.625-1.35L22 2l.6 1.375zm3 7l-3.625-1.625L19 9l3.6 1.65zm-3-4.25v-1.5h4v1.5z");
}

</style>
