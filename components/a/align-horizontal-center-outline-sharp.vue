<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd1_0gbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-horizontal-center-outline-sharp" /></template>
<style>
.yd1_0gbkc {
  fill: currentColor;
  d: path("M11 22v-5H6v-3h5v-4H3V7h8V2h2v5h8v3h-8v4h5v3h-5v5z");
}

</style>
