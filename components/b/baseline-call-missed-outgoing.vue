<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7rpg_3yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-call-missed-outgoing" /></template>
<style>
.t7rpg_3yx {
  fill: currentColor;
  d: path("m3 8.41l9 9l7-7V15h2V7h-8v2h4.59L12 14.59L4.41 7z");
}

</style>
