<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odxisxbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-compress" /></template>
<style>
.odxisxbfp {
  fill: currentColor;
  d: path("M8 19h3v3h2v-3h3l-4-4zm8-15h-3V1h-2v3H8l4 4zM4 9v2h16V9zm0 3h16v2H4z");
}

</style>
