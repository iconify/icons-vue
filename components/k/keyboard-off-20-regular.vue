<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ccuykjbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-off-20-regular" /></template>
<style>
.ccuykjbly {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L14.293 15H3.5A1.5 1.5 0 0 1 2 13.5v-8a1.5 1.5 0 0 1 1.307-1.486l-1.16-1.16a.5.5 0 0 1 0-.707M16.5 4A1.5 1.5 0 0 1 18 5.5v8c0 .644-.406 1.19-.976 1.403L16.121 14h.379a.5.5 0 0 0 .5-.5v-8a.5.5 0 0 0-.5-.5H7.121l-1-1zm-13 1a.5.5 0 0 0-.5.5v8a.5.5 0 0 0 .5.5h9.793l-1-1H5.5a.5.5 0 1 1 0-1h5.793L6.128 6.835a.753.753 0 1 1-.21-.21L4.293 5zm3.498 4a.752.752 0 1 1 0 1.505a.752.752 0 0 1 0-1.505m6.009 0a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m-1.505-2.5a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m3 0a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506");
}

</style>
