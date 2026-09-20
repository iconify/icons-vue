<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6s0unb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hbar" /></template>
<style>
.n6s0unb4j {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.875 21h-2.813v-5.063H6.937V21H4.125V3h2.812v5.062h10.125V3h2.813zM6.937 13.125h10.125v-2.25H6.937z");
}

</style>
