<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rztvod3zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:layout-thin" /></template>
<style>
.rztvod3zt {
  fill: currentColor;
  d: path("M216 44H40a12 12 0 0 0-12 12v144a12 12 0 0 0 12 12h176a12 12 0 0 0 12-12V56a12 12 0 0 0-12-12M40 52h176a4 4 0 0 1 4 4v44H36V56a4 4 0 0 1 4-4m-4 148v-92h64v96H40a4 4 0 0 1-4-4m180 4H108v-96h112v92a4 4 0 0 1-4 4");
}

</style>
