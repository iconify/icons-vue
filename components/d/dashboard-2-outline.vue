<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrwh_hb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-2-outline" /></template>
<style>
.vrwh_hb6f {
  fill: currentColor;
  d: path("M15 20v-7h7v7zm-4-9V4h11v7zm-9 9v-7h11v7zm0-9V4h7v7zm11-2h7V6h-7zm-9 9h7v-3H4zm13 0h3v-3h-3zM4 9h3V6H4zm3 0");
}

</style>
