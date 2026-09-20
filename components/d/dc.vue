<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6m3ambfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dc" /></template>
<style>
.j6m3ambfq {
  fill: var(--svg-color--f30, #f30);
  d: path("m15.28 14.695l-2.16-2.672V6.848l2.313 3.923l1.517-1.138l1.4 2.605zm3.173-2.268L21 17.175H3l3.852-5.508l3.726 3.451l2.43-2.893l2.236 2.772l3.209-2.565zm-11.475-.94l3.582 3.326l2.34-2.795V6.825l-2.155 3.096l-1.472-1.719z");
}

</style>
