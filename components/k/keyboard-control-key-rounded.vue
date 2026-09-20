<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aptcmjbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-control-key-rounded" /></template>
<style>
.aptcmjbvy {
  fill: currentColor;
  d: path("m12 7.114l-5.265 5.24q-.14.14-.332.134q-.191-.007-.337-.154q-.141-.14-.141-.344t.14-.344l5.37-5.369q.242-.243.565-.243t.566.243l5.388 5.388q.14.14.133.342t-.153.347q-.14.14-.334.14t-.334-.14z");
}

</style>
