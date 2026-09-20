<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmtye0bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-off-48-filled" /></template>
<style>
.bmtye0bhh {
  fill: currentColor;
  d: path("m31.232 33l10.634 10.634a1.25 1.25 0 0 0 1.768-1.768l-37.5-37.5a1.25 1.25 0 1 0-1.768 1.768L7.5 9.268V42.75a1.25 1.25 0 1 0 2.5 0V33zm10.018 0h-3.653l-27-27H41.25a1.25 1.25 0 0 1 1.007 1.99L33.801 19.5l8.456 11.51A1.25 1.25 0 0 1 41.25 33");
}

</style>
