<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ove4wgayi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-off-outline-sharp" /></template>
<style>
.ove4wgayi {
  fill: currentColor;
  d: path("m17.733 16.248l-.714-.713L19.75 12l-4.615-6H7.6l-1-1h9.035L21 12zM4 18h11.2L4 6.8zm16.5 5.3L16.2 19H3V5.8L.7 3.5l.708-.708l19.8 19.8zM9.6 12.4");
}

</style>
