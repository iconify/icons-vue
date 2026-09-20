<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ady_bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-square-sharp" /></template>
<style>
.d5ady_bcq {
  fill: currentColor;
  d: path("M11.423 15.923H3.577V8.077h7.846V11.5h9.5v1h-9.5z");
}

</style>
