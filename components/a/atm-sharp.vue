<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7ttrubxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:atm-sharp" /></template>
<style>
.o7ttrubxx {
  fill: currentColor;
  d: path("M10.375 15v-4.5h-2.25V9h6v1.5h-2.25V15zM2 15V9h5v6H5.5v-1.5h-2V15zm1.5-3h2v-1.5h-2zm12 3V9H22v6h-1.5v-4.5h-1V14H18v-3.5h-1V15z");
}

</style>
