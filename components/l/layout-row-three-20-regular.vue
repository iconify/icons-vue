<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pacrv_bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-three-20-regular" /></template>
<style>
.pacrv_bgy {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-2a2 2 0 0 0-2 2v1h12V6a2 2 0 0 0-2-2zm10 4H4v4h12zM4 14a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-1H4z");
}

</style>
