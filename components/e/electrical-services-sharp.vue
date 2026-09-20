<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj56vabqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electrical-services-sharp" /></template>
<style>
.jj56vabqi {
  fill: currentColor;
  d: path("M17.5 14.5v-1h3v1zm0 4v-1h3v1zm-5 1v-2h-2v-3h2v-2h4v7zm-9-3v-7h7v-4h-6v-1h7v6h-7v5h5v1z");
}

</style>
