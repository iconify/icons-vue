<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ctsho7bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-12-filled" /></template>
<style>
.ctsho7bqt {
  fill: currentColor;
  d: path("M9.64 1.069c.808-.311 1.603.484 1.292 1.292l-3.076 7.997c-.349.906-1.654.835-1.9-.104l-.803-3.05a.5.5 0 0 0-.357-.356l-3.05-.803c-.938-.247-1.01-1.552-.104-1.9z");
}

</style>
