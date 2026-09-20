<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l2jwe2b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-circle-48-filled" /></template>
<style>
.l2jwe2b4x {
  fill: currentColor;
  d: path("M24 4c11.046 0 20 8.954 20 20s-8.954 20-20 20S4 35.046 4 24S12.954 4 24 4m8.634 13.616a1.25 1.25 0 0 0-1.666-.091l-.102.091L20.75 27.732l-3.616-3.616a1.25 1.25 0 0 0-1.859 1.666l.091.102l4.5 4.5a1.25 1.25 0 0 0 1.666.091l.102-.091l11-11a1.25 1.25 0 0 0 0-1.768");
}

</style>
