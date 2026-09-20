<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-1-d797w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-missed-outline" /></template>
<style>
.i-1-d797w {
  fill: currentColor;
  d: path("m12 17.425l-7-7V15H3V7h8v2H6.4l5.6 5.6L19.6 7L21 8.425z");
}

</style>
