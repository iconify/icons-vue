<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="suloaubpi"/><path class="mb_xrpbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-latvia" /></template>
<style>
.mb_xrpbdk {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 15h36v6H0z");
}

.suloaubpi {
  fill: var(--svg-color--9e3039, #9e3039);
  d: path("M32 5H4a4 4 0 0 0-4 4v6h36V9a4 4 0 0 0-4-4m0 26H4a4 4 0 0 1-4-4v-6h36v6a4 4 0 0 1-4 4");
}

</style>
