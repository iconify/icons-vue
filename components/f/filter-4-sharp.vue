<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rakj_4tqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-4-sharp" /></template>
<style>
.rakj_4tqk {
  fill: currentColor;
  d: path("M6 18V2h16v16zm-4 4V6h2v14h14v2zm13-7h2V5h-2v4h-2V5h-2v6h4z");
}

</style>
