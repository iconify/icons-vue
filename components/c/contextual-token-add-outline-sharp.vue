<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou_4i3d3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contextual-token-add-outline-sharp" /></template>
<style>
.ou_4i3d3n {
  fill: currentColor;
  d: path("M2 20V4h12v2H4v12h16v-7h2v9zm4-4h7v-3H6zm0-5h7V8H6zm9 5h3v-5h-3zM4 18V6zm14-9V7h-2V5h2V3h2v2h2v2h-2v2z");
}

</style>
