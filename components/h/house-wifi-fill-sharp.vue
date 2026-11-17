<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r76meobax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-wifi-fill-sharp" /></template>
<style>
.r76meobax {
  fill: currentColor;
  d: path("M20.659 9.247c.217.19.341.465.341.753v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0Zm-14.44 3.128a1 1 0 0 0 1.562 1.25a5.3 5.3 0 0 1 1.926-1.521c.717-.337 1.5-.51 2.293-.507a5.34 5.34 0 0 1 2.293.507c.752.35 1.411.871 1.926 1.521a.999.999 0 0 0 1.775-.515a1 1 0 0 0-.213-.735a7.403 7.403 0 0 0-11.562 0m3.074 1.918a.999.999 0 1 0 1.414 1.414A1.82 1.82 0 0 1 12 15.172c.485-.001.951.191 1.293.535a.999.999 0 1 0 1.414-1.414A3.82 3.82 0 0 0 12 13.172a3.82 3.82 0 0 0-2.707 1.121M12.01 17H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
