<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-9s9sbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-flex-end" /></template>
<style>
.t-9s9sbjt {
  fill: currentColor;
  d: path("M3 21v-1h18v1zm8-4V4h2v13z");
}

</style>
