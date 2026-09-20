<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t1-2mybuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:black-small-square" /></template>
<style>
.t1-2mybuz {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M25 24a1 1 0 0 1-1 1H12a1 1 0 0 1-1-1V12a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1z");
}

</style>
