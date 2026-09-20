<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzct7obua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-star" /></template>
<style>
.kzct7obua {
  fill: currentColor;
  d: path("M10.071 13.462L12 12.298l1.929 1.164l-.523-2.196l1.711-1.475l-2.24-.187L12 7.539l-.877 2.065l-2.24.187l1.711 1.475zM6 19.5V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19.5l-6-2.577z");
}

</style>
