<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3iskdbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-highlighter-off-sharp" /></template>
<style>
.k3iskdbsl {
  fill: currentColor;
  d: path("M16.625 13.8L11.2 8.375L17.4 2.2l5.4 5.4zm3.175 8.8l-6-6l-4.5 4.5H7.9l-.75-.75l-.65.65h-5l3.15-3.15l-.75-.75v-1.4l4.5-4.5l-7-7l1.425-1.425l18.4 18.4z");
}

</style>
