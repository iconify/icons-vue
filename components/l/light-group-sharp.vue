<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4qu36xqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:light-group-sharp" /></template>
<style>
.k4qu36xqq {
  fill: currentColor;
  d: path("M3 22v-2h8v2zm14-1q-.825 0-1.412-.587T15 19h-4v-1q0-2.25 1.425-3.9t3.575-2V2h2v10.1q2.175.35 3.588 2T23 18v1h-4q0 .825-.575 1.413T17 21M6 19v-8H.725l2.4-9H10.9l2.4 9H8v8z");
}

</style>
