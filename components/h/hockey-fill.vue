<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pl01tbpgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hockey-fill" /></template>
<style>
.pl01tbpgf {
  fill: currentColor;
  d: path("m149.9 122.82l68-80a8 8 0 0 1 12.2 10.36l-68 80a8 8 0 1 1-12.2-10.36M240 168v32a16 16 0 0 1-16 16h-52.3a16 16 0 0 1-12.19-5.64L25.9 53.18a8 8 0 0 1 12.2-10.36L130.9 152H224a16 16 0 0 1 16 16m-16 0h-16v32h16Zm-108.7 15.06a4 4 0 0 1 0 5.18l-18.81 22.12A16 16 0 0 1 84.3 216H32a16 16 0 0 1-16-16v-32a16 16 0 0 1 16-16h55.05a4 4 0 0 1 3 1.41ZM48 168H32v32h16Z");
}

</style>
