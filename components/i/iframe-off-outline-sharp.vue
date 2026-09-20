<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abagaybhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:iframe-off-outline-sharp" /></template>
<style>
.abagaybhb {
  fill: currentColor;
  d: path("m20.45 23.3l-3.3-3.3H2V4h2v2.85L.65 3.5l1.425-1.425l19.8 19.8zM4 18h11.15l-10-10H4zm16-.85V8h-9.15l-4-4H22v15.15zm-2-2l-1.5-1.5V11.5h-2.15l-1.5-1.5H18z");
}

</style>
