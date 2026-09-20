<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fxoaps5ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-off-20-regular" /></template>
<style>
.fxoaps5ja {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708L6.293 7H3.5a.5.5 0 0 0 0 1h3.793l4 4H3.5a.5.5 0 0 0 0 1h8.793l4.853 4.854a.5.5 0 0 0 .708-.708zM14.12 12l1 1h1.38a.5.5 0 0 0 0-1zm-5-5l1 1h6.38a.5.5 0 0 0 0-1z");
}

</style>
