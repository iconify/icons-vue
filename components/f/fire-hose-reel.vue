<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebdv42e-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-hose-reel" /></template>
<style>
.ebdv42e-q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 9.5q0-3.21 2.27-5.48t5.48-2.27t5.48 2.27t2.27 5.48v6.385q.449.175.792.58q.605.715.451 1.638l-.38 2.28q-.227 1.367-1.613 1.367t-1.613-1.367l-.38-2.28q-.154-.923.451-1.638q.343-.405.792-.58v-1.787q-.345.457-.77.882q-2.27 2.27-5.48 2.27t-5.48-2.27T2.75 9.5m7.76-.75h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
