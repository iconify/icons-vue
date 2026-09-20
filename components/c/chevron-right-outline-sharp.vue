<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0x2xlaud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chevron-right-outline-sharp" /></template>
<style>
.t0x2xlaud {
  fill: currentColor;
  d: path("m13.292 12l-4.6-4.6l.708-.708L14.708 12L9.4 17.308l-.708-.708z");
}

</style>
