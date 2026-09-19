<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ik8-3_bxu"/><path class="emrsycvgy"/><path class="k-wj-qtae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-turkey" /></template>
<style>
.emrsycvgy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M39.778 38.32c-2.302 3.591-7.095 5.856-12.11 4.391c-4.733-1.386-7.984-5.972-7.715-10.918c.262-4.968 3.994-9.193 8.844-10.05c5.139-.913 9.267 1.842 11.03 4.726c-2.089-2.054-4.518-2.979-7.362-2.654c-2.228.256-4.09 1.263-5.548 2.963c-2.854 3.322-2.749 8.304.231 11.439c1.709 1.798 3.811 2.739 6.292 2.762c2.479.018 4.582-.92 6.344-2.654");
}

.ik8-3_bxu {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M64 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11z");
}

.k-wj-qtae {
  fill: var(--svg-color--fff, #fff);
  d: path("m44.23 28.396l2.03 1.884l2.708-.6l-1.167 2.52l1.409 2.381l-2.75-.331l-1.839 2.08l-.531-2.722l-2.548-1.104l2.422-1.344z");
}

</style>
