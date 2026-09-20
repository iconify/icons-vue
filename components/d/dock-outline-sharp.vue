<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4wgqhbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dock-outline-sharp" /></template>
<style>
.n4wgqhbsg {
  fill: currentColor;
  d: path("M8 23v-2h8v2zm8-6V3H8v14zM12 6q.425 0 .713-.288T13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6M8 3v14zM6 19V1h12v4.05h1v3.9h-1V19z");
}

</style>
