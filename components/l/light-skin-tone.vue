<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="o6fhpyk-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:light-skin-tone" /></template>
<style>
.o6fhpyk-a {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffe1bd, #ffe1bd);
}

</style>
