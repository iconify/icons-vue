<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akmc-qr-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:egld" /></template>
<style>
.akmc-qr-d {
  fill: var(--svg-color--23f7dd, #23f7dd);
  d: path("M13.125 12L21 7.785L19.648 5.25l-7.354 2.756a.8.8 0 0 1-.588 0L4.352 5.25L3 7.793L10.875 12L3 16.207l1.352 2.543l7.354-2.756a.8.8 0 0 1 .588 0l7.354 2.756L21 16.193z");
}

</style>
