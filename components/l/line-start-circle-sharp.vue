<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snh65tyqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-circle-sharp" /></template>
<style>
.snh65tyqt {
  fill: currentColor;
  d: path("M8 18q-2.5 0-4.25-1.75T2 12t1.75-4.25T8 6q2.25 0 3.913 1.425T13.925 11H22v2h-8.075q-.35 2.15-2.013 3.575T8 18");
}

</style>
