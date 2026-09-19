<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a-ubeebba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:first-quarter-moon" /></template>
<style>
.a-ubeebba {
  fill: currentColor;
  d: path("M62 32C62 15.432 48.569 2.001 32.001 2H32C15.432 2 2 15.432 2 32s13.432 30 30 30h.001C48.569 61.999 62 48.568 62 32M32 60c-.241 0-.479-.012-.72-.019c-.748-4.34-1.279-15.228-1.279-27.981s.531-23.641 1.279-27.981c.241-.007.479-.019.72-.019c15.465 0 28 12.536 28 28S47.465 60 32 60");
}

</style>
