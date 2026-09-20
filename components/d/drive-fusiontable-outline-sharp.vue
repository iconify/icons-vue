<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk0tvfxzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-fusiontable-outline-sharp" /></template>
<style>
.bk0tvfxzu {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-4.05V19h14v-8.75L13.05 17L9 12.95zm0-2.85l4-4l3.95 3.95L19 7.25V5H5zm0-3.85v-3v6.8v-3.95v6.85v-4V17zm0 3.85V5v9.05v-3.95zm0 2.85v-4V17v-6.75V19z");
}

</style>
