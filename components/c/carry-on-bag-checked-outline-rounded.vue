<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi9qwebmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carry-on-bag-checked-outline-rounded" /></template>
<style>
.oi9qwebmi {
  fill: currentColor;
  d: path("m17.3 18.75l-1.025-1.025q-.15-.15-.375-.15t-.375.15t-.15.375t.15.375L16.6 19.55q.3.3.7.3t.7-.3l2.475-2.475q.15-.15.15-.375t-.15-.375t-.375-.15t-.375.15zM9 19V9H8v10zm-1 2q-.825 0-1.412-.587T6 19V9q0-.825.588-1.412T8 7h6V4h-1q-.425 0-.712-.288T12 3t.288-.712T13 2h2q.425 0 .713.288T16 3v7.675q0 .5-.312.75t-.688.25t-.687-.25t-.313-.75V9h-3v10h.025q.425 0 .713.288t.287.712t-.288.713t-.712.287zm13.538-6.538Q23 15.926 23 18t-1.463 3.538T18 23t-3.537-1.463T13 18t1.463-3.537T18 13t3.538 1.463M9 19V9zm2 0V9z");
}

</style>
