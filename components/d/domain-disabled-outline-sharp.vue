<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igfqzebdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:domain-disabled-outline-sharp" /></template>
<style>
.igfqzebdu {
  fill: currentColor;
  d: path("m21.27 18.15l-1-1V8.154h-8.997l-.542-.542V4.154H7.235l-1-1h5.496v4h9.538zm.5 4.496l-2.504-2.492H2.73V3.608l-1.57-1.57l.708-.707l20.608 20.608zM3.73 19.154h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 8h3v-3h-3zm0-4h3v-3h-3zm4 4h6.535l-3-3h-3.534zm5.77-7h-1v-1h1z");
}

</style>
