<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0hjx3bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-off-sharp" /></template>
<style>
.u0hjx3bex {
  fill: currentColor;
  d: path("M17.733 16.248L6.6 5h9.035L21 12zM20.5 23.3L16.2 19H3V5.8L.7 3.5l.708-.708l19.8 19.8z");
}

</style>
