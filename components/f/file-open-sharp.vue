<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-av3ebsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-open-sharp" /></template>
<style>
.i-av3ebsq {
  fill: currentColor;
  d: path("m21.95 21.664l-3.45-3.45v2.955h-1V16.5h4.67v1h-2.982l3.45 3.45zM14 8h4l-4-4zM5 21V3h9.5L19 7.5v7h-3.5V21z");
}

</style>
