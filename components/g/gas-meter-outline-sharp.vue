<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eez24dbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gas-meter-outline-sharp" /></template>
<style>
.eez24dbsv {
  fill: currentColor;
  d: path("M4 22V4h5V2h2v2h2V2h2v2h5v18zm2-2h12V6H6zm2-10h8V8H8zm4 8q1.05 0 1.775-.712t.725-1.738q0-.825-.475-1.412T12 11.75q-1.575 1.8-2.037 2.4t-.463 1.4q0 1.025.725 1.738T12 18m-6 2V6z");
}

</style>
