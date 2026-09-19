<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lriubg22d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:large-orange-diamond" /></template>
<style>
.lriubg22d {
  fill: var(--svg-color--f6921e, #f6921e);
  d: path("M63 32L32 62.998L1 32L32 1");
}

</style>
