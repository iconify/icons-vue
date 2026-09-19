<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cbs_dha_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:black-large-square" /></template>
<style>
.cbs_dha_p {
  fill: currentColor;
  d: path("M2 2h60v60H2z");
}

</style>
