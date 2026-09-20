<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvqx3mvqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:horizontal-rule-outline-sharp" /></template>
<style>
.wvqx3mvqo {
  fill: currentColor;
  d: path("M5 12.5v-1h14v1z");
}

</style>
