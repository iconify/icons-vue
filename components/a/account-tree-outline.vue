<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl4c-eb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:account-tree-outline" /></template>
<style>
.kl4c-eb2f {
  fill: currentColor;
  d: path("M15 21v-3h-4V8H9v3H2V3h7v3h6V3h7v8h-7V8h-2v8h2v-3h7v8zM4 5v4zm13 10v4zm0-10v4zm0 4h3V5h-3zm0 10h3v-4h-3zM4 9h3V5H4z");
}

</style>
