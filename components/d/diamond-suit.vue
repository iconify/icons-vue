<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lypxc0e1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:diamond-suit" /></template>
<style>
.lypxc0e1x {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("M2.018 32L32 2.02L61.98 32L32 61.981z");
}

</style>
