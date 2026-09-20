<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mtpeitfnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-off-20-filled" /></template>
<style>
.mtpeitfnd {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708L4 4.707V17.5a.5.5 0 0 0 1 0V13h7.293l4.853 4.854a.5.5 0 0 0 .708-.708zM16.5 13h-1.379l-10-10H16.5a.5.5 0 0 1 .416.777L14.101 8l2.815 4.223A.5.5 0 0 1 16.5 13");
}

</style>
