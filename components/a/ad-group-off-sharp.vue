<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or7uc5buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ad-group-off-sharp" /></template>
<style>
.or7uc5buq {
  fill: currentColor;
  d: path("M20.5 23.3L15.2 18H6V8.8L.7 3.5l1.4-1.4l19.8 19.8zM2 22V6h2v14h14v2zm18.7-4.125L8.825 6H20V4H8v1.175L6.125 3.3V2H22v15.875z");
}

</style>
