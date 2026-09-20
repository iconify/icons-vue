<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ake2d7bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-outline-rounded" /></template>
<style>
.ake2d7bhw {
  fill: currentColor;
  d: path("M19.5 14.5q-.775 0-1.4-.425T17.2 13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h14.2q.275-.65.9-1.075t1.4-.425q1.05 0 1.775.725T22 12t-.725 1.775t-1.775.725");
}

</style>
