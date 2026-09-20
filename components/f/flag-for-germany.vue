<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qjvxstb6d"/><path class="q-qbtn3dt"/><path class="qjotn_bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-germany" /></template>
<style>
.q-qbtn3dt {
  fill: var(--svg-color--ed1f24, #ed1f24);
  d: path("M0 14h36v9H0z");
}

.qjotn_bkb {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

.qjvxstb6d {
  fill: var(--svg-color--ffcd05, #ffcd05);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4H0z");
}

</style>
