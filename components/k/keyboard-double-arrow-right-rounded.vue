<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3ea_ebjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-double-arrow-right-rounded" /></template>
<style>
.u3ea_ebjk {
  fill: currentColor;
  d: path("m10.537 12l-4.24-4.246q-.141-.14-.154-.341t.153-.367q.16-.16.354-.16t.354.16l4.388 4.389q.131.13.184.267t.053.298t-.053.298t-.184.268l-4.388 4.388q-.14.14-.341.153t-.367-.153q-.16-.16-.16-.354t.16-.354zm6.1 0l-4.24-4.246q-.141-.14-.154-.341t.153-.367q.16-.16.354-.16t.354.16l4.388 4.389q.131.13.184.267t.053.298t-.053.298t-.184.268l-4.388 4.388q-.14.14-.341.153t-.367-.153q-.16-.16-.16-.354t.16-.354z");
}

</style>
