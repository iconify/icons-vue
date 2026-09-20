<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc3-n8clw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-copy-off-sharp" /></template>
<style>
.fc3-n8clw {
  fill: currentColor;
  d: path("m21 18.15l-15-15V1h9l6 6zm-.5 5.15L16.2 19H6V8.8L.7 3.5l1.4-1.4l19.8 19.8zM14 8h5.5L14 2.5L19.5 8L14 2.5zM2 23V8h2v13h12v2z");
}

</style>
