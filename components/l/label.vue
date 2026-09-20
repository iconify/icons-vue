<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2tbzsbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label" /></template>
<style>
.a2tbzsbgt {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h11q.475 0 .9.213t.7.587L22 12l-5.4 7.2q-.275.375-.7.588T15 20z");
}

</style>
