<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1zi16b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:euroe" /></template>
<style>
.b1zi16b4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 3h18v3.214H6.214v1.929H21v3.214H3zm0 9.643h18v3.214H6.214v1.929H21V21H3z");
}

</style>
