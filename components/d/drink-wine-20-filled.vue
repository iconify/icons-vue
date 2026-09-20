<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qfghhtjll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drink-wine-20-filled" /></template>
<style>
.qfghhtjll {
  fill: currentColor;
  d: path("M5.5 2a.5.5 0 0 0-.5.5V8a5 5 0 0 0 4.5 4.975V17h-2a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1h-2v-4.025A5 5 0 0 0 15 8V2.5a.5.5 0 0 0-.5-.5zM6 5.5V3h8v2.5zm7.452 2.575a3.5 3.5 0 0 1-2.867 2.876a.5.5 0 1 1-.167-.986a2.5 2.5 0 0 0 2.048-2.054a.5.5 0 0 1 .986.164");
}

</style>
