<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk0r5pbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-curtains" /></template>
<style>
.rk0r5pbjb {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM8.19 12c2.04-1.35 3.5-3.94 3.76-7h.09c.26 3.06 1.72 5.65 3.76 7c-2.04 1.35-3.5 3.94-3.76 7h-.09c-.26-3.06-1.72-5.65-3.76-7");
}

</style>
