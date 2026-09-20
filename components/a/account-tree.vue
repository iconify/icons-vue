<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4fkknl6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:account-tree" /></template>
<style>
.u4fkknl6y {
  fill: currentColor;
  d: path("M15 21v-3h-4V8H9v3H2V3h7v3h6V3h7v8h-7V8h-2v8h2v-3h7v8z");
}

</style>
