<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcm4_ib0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-low-sharp" /></template>
<style>
.xcm4_ib0f {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10zm2-2h11V9H6z");
}

</style>
