<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj9crxbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-to-queue-sharp" /></template>
<style>
.vj9crxbto {
  fill: currentColor;
  d: path("M11 15h2v-3h3v-2h-3V7h-2v3H8v2h3zm-3 6v-2H2V3h20v16h-6v2z");
}

</style>
