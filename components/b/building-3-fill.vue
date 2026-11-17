<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzci7nb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-fill" /></template>
<style>
.yzci7nb_p {
  fill: currentColor;
  d: path("M6 4a1 1 0 0 1 1-1h10a3 3 0 0 1 3 3v13h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-5.039c0-.911.414-1.773 1.126-2.342l.874-.7Zm2.126 5.219a3 3 0 0 1 3.748 0l3 2.4A3 3 0 0 1 16 13.961V19h2V6a1 1 0 0 0-1-1H8v4.319Z");
}

</style>
