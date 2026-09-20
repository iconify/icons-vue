<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntw9sfhjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-portrait-2-outline-sharp" /></template>
<style>
.ntw9sfhjl {
  fill: currentColor;
  d: path("M8 11h6V6H8zm12 11H4V2h16zm-2-2V4H6v16zm0-16H6z");
}

</style>
