<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w107djeae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cleaning-services-sharp" /></template>
<style>
.w107djeae {
  fill: currentColor;
  d: path("M4 22V11.712h5.712V2h4.577v9.712H20V22zm1-1h2.75v-4.02h1V21h2.75v-4.02h1V21h2.75v-4.02h1V21H19v-8.288H5z");
}

</style>
