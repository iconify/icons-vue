<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qivtypbfs"/><path class="ty5r6tb3i"/><path class="demm-xb4v"/><path class="rxfc5bb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-pakistan" /></template>
<style>
.demm-xb4v {
  fill: var(--svg-color--fff, #FFF);
  d: path("M29.572 11.775l-2.17.924l-1.548-1.779l.207 2.349l-2.17.924l2.298.528l.208 2.349l1.213-2.022l2.298.529l-1.548-1.779z");
}

.qivtypbfs {
  fill: var(--svg-color--004600, #004600);
  d: path("M32 5H9v26h23a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4zm-9.5 20.472a7.5 7.5 0 0 1-7.5-7.5c0-3.72 2.711-6.799 6.263-7.39A6.496 6.496 0 0 0 24 22.972a6.496 6.496 0 0 0 5.89-3.763c-.591 3.553-3.67 6.263-7.39 6.263zm5.11-10.424l-1.213 2.022l-.208-2.349l-2.298-.528l2.17-.924l-.207-2.349l1.548 1.779l2.17-.924l-1.212 2.023l1.548 1.779l-2.298-.529z");
}

.rxfc5bb2o {
  fill: var(--svg-color--fff, #FFF);
  d: path("M24 22.972a6.496 6.496 0 0 1-2.737-12.39c-3.552.592-6.263 3.671-6.263 7.39a7.5 7.5 0 0 0 7.5 7.5c3.72 0 6.799-2.711 7.39-6.263A6.494 6.494 0 0 1 24 22.972z");
}

.ty5r6tb3i {
  fill: var(--svg-color--eee, #EEE);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h5V5H4z");
}

</style>
