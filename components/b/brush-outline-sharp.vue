<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs9mwrz6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brush-outline-sharp" /></template>
<style>
.vs9mwrz6b {
  fill: currentColor;
  d: path("M6.385 19.616q-.592 0-1.17-.204t-1.023-.566q.497-.327.845-.878t.348-1.352q0-.847.577-1.424q.577-.576 1.423-.576t1.423.576t.577 1.424q0 1.237-.882 2.118t-2.118.881m0-1q.825 0 1.412-.587t.588-1.412q0-.425-.288-.713t-.712-.288t-.713.288t-.287.713q0 .575-.138 1.05t-.362.9q.125.05.25.05zM11.25 14.5l-1.711-1.711l8.88-8.881l1.712 1.711zm-3.866 2.116");
}

</style>
