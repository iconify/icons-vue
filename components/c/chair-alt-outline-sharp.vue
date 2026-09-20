<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksyx6hg_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chair-alt-outline-sharp" /></template>
<style>
.ksyx6hg_o {
  fill: currentColor;
  d: path("M5 21v-9h3v-2H5V3h14v7h-3v2h3v9h-2v-3H7v3zM7 8h10V5H7zm3 4h4v-2h-4zm-3 4h10v-2H7zm0-8V5zm0 8v-2z");
}

</style>
