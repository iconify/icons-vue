<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n19rjccuv"/><path class="wy3cybejb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:black-square-button" /></template>
<style>
.n19rjccuv {
  fill: var(--svg-color--333, #333);
  d: path("M2 2h60v60H2z");
}

.wy3cybejb {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M10 10h44v44H10z");
}

</style>
