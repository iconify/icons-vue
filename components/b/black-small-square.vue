<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mh07l-bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:black-small-square" /></template>
<style>
.mh07l-bzv {
  fill: currentColor;
  d: path("M16 16h32v32H16z");
}

</style>
