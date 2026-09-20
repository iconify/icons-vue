<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7q8eobjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-sensor-sharp" /></template>
<style>
.z7q8eobjl {
  fill: currentColor;
  d: path("M8 20v-3.73h5.539v-2.54H8V4h8v16zm-2.615-4.5v-1h7.384v1zm7.155-5.96q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M19 8.5v-5h1v5z");
}

</style>
