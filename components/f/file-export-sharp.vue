<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp7icdbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-export-sharp" /></template>
<style>
.tp7icdbra {
  fill: currentColor;
  d: path("m5.05 22.375l-1.4-1.425L6.6 18H4.35v-2H10v5.65H8v-2.225zM12 22v-8H4V2h10l6 6v14zm1-13h5l-5-5l5 5l-5-5z");
}

</style>
