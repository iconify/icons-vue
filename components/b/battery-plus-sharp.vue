<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiu48n3gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-plus-sharp" /></template>
<style>
.qiu48n3gf {
  fill: currentColor;
  d: path("M16 22v-3h-3v-2h3v-3h2v3h3v2h-3v3zm-9 0V4h3V2h4v2h3v8q-.2 0-.4.013t-.4.037q-2.2.3-3.7 1.975T11 18q0 1.125.4 2.15T12.525 22z");
}

</style>
