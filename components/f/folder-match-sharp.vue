<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-g92oqfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-match-sharp" /></template>
<style>
.w-g92oqfl {
  fill: currentColor;
  d: path("M9 19.4q-2.025-.8-3.338-2.512T4.076 13H6.1q.225 1.325.975 2.425T9 17.2zm2 2.6v-9h4.5l1 1.5H22V22zM2 11V2h4.5l1 1.5H13V11zm16 1q0-1.625-.8-3.012T15 6.8V4.6q2.275.925 3.638 2.938T20 12z");
}

</style>
