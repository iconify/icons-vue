<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wtypthf3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:element-2" /></template>
<style>
.wtypthf3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.053 32.736V42.5L24 33.1L7.947 42.5v-9.764L24 23.336zm0-17.837v9.764L24 15.264l-16.053 9.4v-9.765L24 5.5z");
}

</style>
