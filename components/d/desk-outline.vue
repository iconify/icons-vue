<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvtcp1b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desk-outline" /></template>
<style>
.dvtcp1b1f {
  fill: currentColor;
  d: path("M2 18V6h20v12h-2v-2h-4v2h-2V8H4v10zm14-8h4V8h-4zm0 4h4v-2h-4z");
}

</style>
