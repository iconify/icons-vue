<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmc8ugjrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lan-sharp" /></template>
<style>
.pmc8ugjrz {
  fill: currentColor;
  d: path("M3.5 21.5v-6h3v-4h5v-3h-3v-6h7v6h-3v3h5v4h3v6h-7v-6h3v-3h-9v3h3v6z");
}

</style>
