<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc3gskb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-off-outline-sharp" /></template>
<style>
.mc3gskb2g {
  fill: currentColor;
  d: path("M19.85 22.525L1.475 4.15L2.9 2.725L21.275 21.1zM8 16v-2h6.175l2 2zm-3-3v-2h2v2zm3 0v-2h2v2zm9 0v-2h2v2zM5 10V8h2v2zm9 0V8h2v2zm3 0V8h2v2zm3 7V7h-9.975l-2-2H22v14.025zM2 19V5h3.175l2 2H4v10h13.175l2 2zm9.025-11H13v1.975zM14 11h2v1.975zm1 1");
}

</style>
