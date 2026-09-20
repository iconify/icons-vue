<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zahc1pw0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-32-regular" /></template>
<style>
.zahc1pw0n {
  fill: currentColor;
  d: path("M10.103 3.368A2 2 0 0 1 12 2h9a2 2 0 0 1 1.873 2.702L20.886 10H24a2 2 0 0 1 1.54 3.276L12.473 29.047c-1.706 2.058-5.016.365-4.346-2.222L10.415 18H8a2 2 0 0 1-1.897-2.633zM12 4L8 16h3.708a1 1 0 0 1 .968 1.251l-2.613 10.076c-.134.517.528.856.87.444L24 12h-4.557a1 1 0 0 1-.936-1.351L21 4z");
}

</style>
