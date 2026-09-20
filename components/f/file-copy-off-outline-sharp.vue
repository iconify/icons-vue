<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8dgnzbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-copy-off-outline-sharp" /></template>
<style>
.y8dgnzbfg {
  fill: currentColor;
  d: path("m21 18.15l-2-2V8h-5V3H8v2.15l-2-2V1h9l6 6zM8 17h6.2L8 10.8zm12.5 6.3L16.2 19H6V8.8L.7 3.5l1.4-1.4l19.8 19.8zM2 23V8h2v13h12v2z");
}

</style>
