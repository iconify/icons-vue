<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccpxfdb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fast-forward-sharp" /></template>
<style>
.ccpxfdb4y {
  fill: currentColor;
  d: path("M2.5 18V6l9 6zm10 0V6l9 6z");
}

</style>
