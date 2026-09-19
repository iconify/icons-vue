<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a93huobqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-align-horizontal-right" /></template>
<style>
.a93huobqi {
  fill: currentColor;
  d: path("M20 2h2v20h-2zM2 10h16V7H2zm6 7h10v-3H8z");
}

</style>
