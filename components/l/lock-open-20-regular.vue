<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="unge2zbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-open-20-regular" /></template>
<style>
.unge2zbzv {
  fill: currentColor;
  d: path("M15 1a4 4 0 0 1 4 4v.5a.5.5 0 0 1-1 0V5a3 3 0 1 0-6 0v2h1.5A2.5 2.5 0 0 1 16 9.5v6a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 4 15.5v-6A2.5 2.5 0 0 1 6.5 7H11V5a4 4 0 0 1 4-4M6.5 8A1.5 1.5 0 0 0 5 9.5v6A1.5 1.5 0 0 0 6.5 17h7a1.5 1.5 0 0 0 1.5-1.5v-6A1.5 1.5 0 0 0 13.5 8zm3.5 3.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
