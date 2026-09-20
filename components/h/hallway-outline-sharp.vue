<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdl7fqbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hallway-outline-sharp" /></template>
<style>
.tdl7fqbai {
  fill: currentColor;
  d: path("M3 22V4h5l4-4l4 4h5v18zm2-2h14V6H5zm1-2h12l-3.75-5l-3 4L9 14zm4.1-14h3.8L12 2.1zM5 20V6z");
}

</style>
