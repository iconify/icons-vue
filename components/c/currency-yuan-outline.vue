<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qabykrbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-yuan-outline" /></template>
<style>
.qabykrbxw {
  fill: currentColor;
  d: path("M11.5 20v-6.5h-5v-1h4.802L5.904 4h1.202L12 11.742L16.894 4h1.202l-5.398 8.5H17.5v1h-5V20z");
}

</style>
