<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y78mouq8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-wifi-fill-round" /></template>
<style>
.y78mouq8f {
  fill: currentColor;
  d: path("M16 22H8a5 5 0 0 1-5-5v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22m-9.781-9.625a1 1 0 0 0 1.562 1.25a5.3 5.3 0 0 1 1.926-1.521c.717-.337 1.5-.51 2.293-.507a5.34 5.34 0 0 1 2.293.507c.752.35 1.411.871 1.926 1.521a.999.999 0 0 0 1.775-.515a1 1 0 0 0-.213-.735a7.403 7.403 0 0 0-11.562 0m3.074 1.918a.999.999 0 1 0 1.414 1.414A1.82 1.82 0 0 1 12 15.172c.485-.001.951.191 1.293.535a.999.999 0 1 0 1.414-1.414A3.82 3.82 0 0 0 12 13.172a3.82 3.82 0 0 0-2.707 1.121M12.01 17H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
