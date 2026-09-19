<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr5eec-en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:flash-off" /></template>
<style>
.tr5eec-en {
  fill: currentColor;
  d: path("M3.27 3L2 4.27l5 5V13h3v9l3.58-6.14L17.73 20L19 18.73zM17 10h-4l4-8H7v2.18l8.46 8.46z");
}

</style>
