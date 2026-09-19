<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3tq17tbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-wb-twilight" /></template>
<style>
.a3tq17tbu {
  fill: currentColor;
  d: path("m16.955 8.662l2.12-2.122l1.416 1.414l-2.121 2.122zM2 18h20v2H2zm9-14h2v3h-2zM3.543 7.925L4.957 6.51l2.121 2.12l-1.414 1.415zM5 16h14c0-3.87-3.13-7-7-7s-7 3.13-7 7");
}

</style>
