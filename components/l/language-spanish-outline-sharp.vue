<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avm00-dxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-spanish-outline-sharp" /></template>
<style>
.avm00-dxd {
  fill: currentColor;
  d: path("M13 17v-3h2v1h3v-2h-5V7h7v3h-2V9h-3v2h5v6zM4 7h7v2H6v2h4v2H6v2h5v2H4z");
}

</style>
