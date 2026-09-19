<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="kwv23tbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:dark-skin-tone" /></template>
<style>
.kwv23tbku {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--8a6859, #8a6859);
}

</style>
