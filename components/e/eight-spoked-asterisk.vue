<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="l_wxmtbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:eight-spoked-asterisk" /></template>
<style>
.l_wxmtbbz {
  fill: currentColor;
  d: path("m62 32l-24.166-2.417l15.379-18.797l-18.797 15.38L32 2l-2.417 24.166l-18.797-15.38l15.38 18.797L2 32l24.166 2.416l-15.38 18.797l18.797-15.379L32 62l2.416-24.166l18.797 15.379l-15.379-18.797z");
}

</style>
