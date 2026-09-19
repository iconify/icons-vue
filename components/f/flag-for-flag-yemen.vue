<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e2c785bsu"/><path class="yhgdzpbsm"/><path class="mh79h9x1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-yemen" /></template>
<style>
.e2c785bsu {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

.mh79h9x1l {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

.yhgdzpbsm {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

</style>
