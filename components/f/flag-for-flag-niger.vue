<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="eubhabc9r"/><path class="wgvt4gb3r"/><circle class="t5ukn_65z"/><path class="nwp54hbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-niger" /></template>
<style>
.eubhabc9r {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 13h36v10H0z");
}

.nwp54hbrh {
  fill: var(--svg-color--0db02b, #0DB02B);
  d: path("M32 31H4a4 4 0 0 1-4-4v-4h36v4a4 4 0 0 1-4 4z");
}

.t5ukn_65z {
  fill: var(--svg-color--e05206, #E05206);
  cx: 18px;
  cy: 18px;
  r: 4px;
}

.wgvt4gb3r {
  fill: var(--svg-color--e05206, #E05206);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4z");
}

</style>
