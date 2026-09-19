<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ry69nsbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:black-medium-square" /></template>
<style>
.ry69nsbrv {
  fill: var(--svg-color--333, #333);
  d: path("M8 8h48v48H8z");
}

</style>
