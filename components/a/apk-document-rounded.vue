<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvlk1-flm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-document-rounded" /></template>
<style>
.vvlk1-flm {
  fill: currentColor;
  d: path("M7.962 18.23h8.076q-.079-.987-.595-1.813q-.516-.827-1.374-1.311l.767-1.373q.041-.081.006-.177q-.034-.096-.127-.146q-.074-.05-.158-.026t-.124.106l-.792 1.404q-.385-.161-.796-.245t-.842-.083t-.836.086t-.807.242l-.783-1.404q-.05-.086-.143-.106q-.093-.019-.18.031q-.02 0-.081.318l.777 1.373q-.852.484-1.38 1.31t-.608 1.815m1.948-1.333q-.121-.121-.121-.283t.12-.282t.283-.121t.274.12t.111.284t-.111.282t-.274.121t-.282-.121m3.634 0q-.121-.121-.121-.283t.121-.282t.283-.121t.283.12q.12.122.12.284t-.12.282q-.121.121-.283.121t-.283-.121M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h7.213q.331 0 .632.13t.518.349L18.52 7.02q.217.218.348.518t.131.632v11.214q0 .69-.463 1.153T17.385 21zM14 7.2q0 .34.23.57t.57.23H18l-4-4z");
}

</style>
