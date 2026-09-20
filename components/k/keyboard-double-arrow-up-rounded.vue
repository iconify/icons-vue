<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osbt9pqqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-double-arrow-up-rounded" /></template>
<style>
.osbt9pqqk {
  fill: currentColor;
  d: path("m12 13.114l-4.246 4.24q-.14.14-.341.153t-.367-.153q-.16-.16-.16-.354t.16-.354l4.389-4.388q.13-.131.267-.184t.298-.053t.298.053t.268.184l4.388 4.388q.14.14.153.341t-.153.367q-.16.16-.354.16t-.354-.16zm0-6l-4.246 4.24q-.14.14-.341.153t-.367-.153q-.16-.16-.16-.354t.16-.354l4.389-4.388q.13-.131.267-.184T12 6.021t.298.053t.268.184l4.388 4.388q.14.14.153.341t-.153.367q-.16.16-.354.16t-.354-.16z");
}

</style>
