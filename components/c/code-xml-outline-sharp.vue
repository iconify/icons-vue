<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms8n33b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:code-xml-outline-sharp" /></template>
<style>
.ms8n33b4d {
  fill: currentColor;
  d: path("M6 16.289L1.712 12L6 7.712l.708.688L3.114 12l3.594 3.6zm4.123 3.376l-.938-.292l4.692-15.038l.958.292zM18 16.29l-.708-.689l3.595-3.6l-3.595-3.6l.708-.689L22.288 12z");
}

</style>
