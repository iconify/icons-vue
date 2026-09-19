<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x6bpzjfoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:black-medium-small-square" /></template>
<style>
.x6bpzjfoq {
  fill: var(--svg-color--354a54, #354a54);
  d: path("M48.566 44.991a3.57 3.57 0 0 1-3.572 3.575H19.005c-1.972 0-3.57-1.6-3.57-3.575V19.005a3.57 3.57 0 0 1 3.57-3.572h25.989c1.975 0 3.572 1.6 3.572 3.572z");
}

</style>
