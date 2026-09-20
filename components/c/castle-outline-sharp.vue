<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frfzk0bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:castle-outline-sharp" /></template>
<style>
.frfzk0bpb {
  fill: currentColor;
  d: path("M1 21V9h2v2h2V3h2v2h2V3h2v2h2V3h2v2h2V3h2v8h2V9h2v12h-9v-5h-4v5zm2-2h5v-5h8v5h5v-6h-4V7H7v6H3zm6-7h2V9H9zm4 0h2V9h-2zm-1 1");
}

</style>
