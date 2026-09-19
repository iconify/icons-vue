<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n19rjccuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:black-large-square" /></template>
<style>
.n19rjccuv {
  fill: var(--svg-color--333, #333);
  d: path("M2 2h60v60H2z");
}

</style>
