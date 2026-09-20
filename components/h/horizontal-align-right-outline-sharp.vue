<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc3q5nphy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:horizontal-align-right-outline-sharp" /></template>
<style>
.zc3q5nphy {
  fill: currentColor;
  d: path("M19 19V5h1v14zm-7-2.692l-.708-.708l3.1-3.1H4v-1h10.392l-3.1-3.1l.708-.708L16.308 12z");
}

</style>
