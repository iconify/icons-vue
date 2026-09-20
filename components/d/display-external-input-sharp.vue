<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4xbkb7zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-external-input-sharp" /></template>
<style>
.q4xbkb7zs {
  fill: currentColor;
  d: path("m17.442 21.789l-.713-.714L18.809 19h-4.867v-1h4.887l-2.094-2.1l.707-.688l3.289 3.288zM4 20v-5h1v4h4v1zM4 9V4h5v1H5v4zm15 0V5h-4V4h5v5z");
}

</style>
