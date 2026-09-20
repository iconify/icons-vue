<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk79asbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eurt" /></template>
<style>
.hk79asbxz {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 17.4h10.2V21H4.8V3h13.8v3.6H9v3.6h9v3.6H9z");
}

</style>
