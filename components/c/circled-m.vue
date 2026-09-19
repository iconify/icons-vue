<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mzdj0rbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:circled-m" /></template>
<style>
.mzdj0rbpk {
  fill: currentColor;
  d: path("M32 2C15.431 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m15 47h-6V24l-9 9l-9-9v25h-6V15h6l9 9l9-9h6z");
}

</style>
