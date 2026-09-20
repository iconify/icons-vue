<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsh6nkbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bolt-outline" /></template>
<style>
.wsh6nkbkb {
  fill: currentColor;
  d: path("m10.55 18.2l5.175-6.2h-4l.725-5.675L7.825 13H11.3zM8 22l1-7H4l9-13h2l-1 8h6L10 22zm3.775-9.75");
}

</style>
