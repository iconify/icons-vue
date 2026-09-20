<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azbflcgnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:experiment-sharp" /></template>
<style>
.azbflcgnm {
  fill: currentColor;
  d: path("M5 20q-.64 0-.909-.57t.128-1.065L10 11.346V5H8.116V4h7.769v1H14v6.346l5.78 7.02q.397.494.129 1.064T19 20zm2-2h10l-3.4-4h-3.2z");
}

</style>
