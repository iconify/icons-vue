<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9__dtx8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:burst-mode-sharp" /></template>
<style>
.y9__dtx8q {
  fill: currentColor;
  d: path("M1 19V5h2v14zm4 0V5h2v14zm4 0V5h14v14zm3-4h8l-2.6-3.5l-1.9 2.5l-1.4-1.85z");
}

</style>
