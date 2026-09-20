<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd_21ybya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-triangle-sharp" /></template>
<style>
.pd_21ybya {
  fill: currentColor;
  d: path("M1 20L12 1l11 19zm10-3.5h2v-2h2v-2h-2v-2h-2v2H9v2h2z");
}

</style>
