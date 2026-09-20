<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hayk-eb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-20-filled" /></template>
<style>
.hayk-eb2p {
  fill: currentColor;
  d: path("m7.032 13.907l-3.471-3.905a.75.75 0 0 0-1.122.996l4 4.5a.75.75 0 0 0 1.091.032l10.5-10.5a.75.75 0 0 0-1.06-1.06z");
}

</style>
