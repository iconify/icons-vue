<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9oahubvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-document-sharp" /></template>
<style>
.b9oahubvw {
  fill: currentColor;
  d: path("M7.962 18.23h8.076q-.079-.987-.595-1.813q-.516-.827-1.374-1.311l.767-1.373q.041-.081.006-.177q-.034-.096-.127-.146q-.074-.05-.158-.026t-.124.106l-.792 1.404q-.385-.161-.796-.245t-.842-.083t-.836.086t-.807.242l-.783-1.404q-.05-.086-.143-.106q-.093-.019-.18.031q-.02 0-.081.318l.777 1.373q-.852.484-1.38 1.31t-.608 1.815m1.948-1.333q-.121-.121-.121-.283t.12-.282t.283-.121t.274.12t.111.284t-.111.282t-.274.121t-.282-.121m3.634 0q-.121-.121-.121-.283t.121-.282t.283-.121t.283.12q.12.122.12.284t-.12.282q-.121.121-.283.121t-.283-.121M5 21V3h9.5L19 7.5V21zm9-13h4l-4-4z");
}

</style>
