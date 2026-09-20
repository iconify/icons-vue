<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l3pmqbcri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-16-regular" /></template>
<style>
.l3pmqbcri {
  fill: currentColor;
  d: path("M12.763 1.075A.5.5 0 0 1 13 1.5v5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.224-.947l10-5a.5.5 0 0 1 .487.022M4.618 6H12V2.309zM13 14.5a.5.5 0 0 1-.724.447l-10-5A.5.5 0 0 1 2.5 9h10a.5.5 0 0 1 .5.5z");
}

</style>
