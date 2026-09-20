<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="ssvg-id-digit-onea" gradientUnits="userSpaceOnUse" x1="59.335" y1="100.333" x2="59.335" y2="25.95" gradientTransform="matrix(1 0 0 -1 0 128)"><stop offset="0" class="vlzxxcccm"/><stop offset=".515" class="fboms9lpk"/></linearGradient><path fill="url(#ssvg-id-digit-onea)" class="oobb4dbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:digit-one" /></template>
<style>
.fboms9lpk {
  stop-color: var(--svg-color--504f4f, #504f4f);
}

.oobb4dbkf {
  d: path("M73.57 102.07H63.7c-.76 0-1.37-.61-1.37-1.37V43.03c0-.94-.92-1.6-1.81-1.3l-14.98 5.11c-.89.3-1.81-.36-1.81-1.3v-7.76c0-.57.36-1.09.9-1.29L73.1 26.02c.15-.06.31-.08.47-.08c.76 0 1.37.61 1.37 1.37v73.39c0 .75-.61 1.37-1.37 1.37z");
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

</style>
