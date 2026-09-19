<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t27nw4i7p"/><path class="gctiwgbdz"/><path class="qumbj19mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-costa-rica" /></template>
<style>
.gctiwgbdz {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M2 32c0 4.3.9 8.3 2.5 12h55c1.6-3.7 2.5-7.7 2.5-12s-.9-8.3-2.5-12h-55C2.9 23.7 2 27.7 2 32");
}

.qumbj19mw {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M11.6 54h40.7c3-2.8 5.5-6.2 7.1-10h-55c1.8 3.8 4.2 7.2 7.2 10m40.8-44H11.6c-3 2.8-5.5 6.2-7.1 10h55c-1.7-3.8-4.1-7.2-7.1-10");
}

.t27nw4i7p {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M52.4 10C47 5 39.9 2 32 2s-15 3-20.4 8zM11.6 54c5.4 5 12.5 8 20.4 8s15-3 20.4-8z");
}

</style>
