<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjvteewdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-franc-outline-rounded" /></template>
<style>
.pjvteewdi {
  fill: currentColor;
  d: path("M7.692 19.5V17h-1.5q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h1.5V4.808q0-.343.233-.576T8.5 4h8.308q.212 0 .356.144t.144.357t-.144.356t-.356.143H8.692v6.308h7.116q.212 0 .356.144t.144.356t-.144.357t-.356.143H8.692V16H12q.213 0 .356.144t.144.357t-.144.356T12 17H8.692v2.5q0 .213-.144.356q-.144.144-.356.144q-.213 0-.357-.144t-.143-.356");
}

</style>
