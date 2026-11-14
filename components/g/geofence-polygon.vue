<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8gghgb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:geofence-polygon" /></template>
<style>
.u8gghgb8i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.842 6.334l5.591-3.993q.902-.644 1.984-.409l9.424 2.048q1.885.409 1.967 2.336l.395 9.1q.065 1.502-1.23 2.263l-6.853 4.032q-1.057.622-2.196.166l-8.161-3.264q-1.488-.595-1.568-2.197l-.396-7.924q-.068-1.364 1.043-2.158M12.01 10H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12.01 10");
}

</style>
